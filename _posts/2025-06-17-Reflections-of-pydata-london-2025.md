# Reflections on PyData London 2025

*By Jiarui Cao, 21st June 2025*

![PyData London 2025](/images/pydata_london_2025/pydata_day1_01.jpeg)

I have attended and volunteered at PyData London 2025 between 6-8 June. It was a fantastic few days of talks, tools, community, and learning.


## Most Popular Topics and Tools


On my very biased opinion, I have identified 3 key topics:

1. **GPU**: NVIDIA has developed a suite of open source libraries -- [RAPIDS](https://developer.nvidia.com/rapids) to the most popular tools in Python community. 
2. **Polars**: Polars has been really popular in the past few years and this year we see tools and ecosystem built on top of it.  
3. **LLM**: no surprise, LLM and agents are still the hot topic. 

## Talks I Attended and Really Liked

A list of talks I attended and particularly enjoyed — with a few notes on why they resonated.


- **Tutorial GPU Accelerated Python**  
  Speaker: Jacob Tomlinson and NVIDIA team  
  Key takeaways:
  ![rapids](/images/pydata_london_2025/rapids.png)
  - How to use CUDA with Python
  - How to use Numba to write kernel function 
  - CuPy: Numpy/SciPy-compatible library with GPU
  - cuDF: supports 100% of the pandas API


- **Parallel PyTorch Inference with Python Free-Threading**  
  Speaker: Michał Szołucha (NVIDIA)
  Key takeaways: 
    - Python has (almost) removed GIL from 3.13.
    - GPU can run faster. 
    - So can/will PyTorch. 


- [**NetworkX is Fast Now: Zero Code Change Acceleration**](https://cfp.pydata.org/london2025/talk/XTU8RH/)
  Speaker: Mridul Seth
  Key takeaways: 
    - NetworkX is popular and people love it (I certainly do!) 
    - NetworkX too slow for hugh graphs? Accelerate its backend, there are many options. Such as GraphBLAS and nx-cugraph 

- **One repo to rule them all, one repo to bind them...Control all of your projects with copier!**
  Speaker: Tim Paine
  Key takeaways: 
    - `copier` (https://copier.readthedocs.io/en/stable/) is a fantastic tool—a library and CLI app that helps render and manage project templates effortlessly.

- **Polars, DuckDB, PySpark, PyArrow, pandas, cuDF: how Narwhals has brought them all together!**
    Speaker: Marco Gorelli
    Key takeaways: 
    - Narwhals (https://lnkd.in/gjVMnX9A) provides a lightweight, extensible compatibility layer for working across dataframe libraries. Super useful for tool developers.



## New Open Source Tools I Want to Try

A short list of new tools or libraries I discovered that I’m excited to try out:

- [CuPy](https://cupy.dev/) - numpy/scipy with GPU
- [RAPIS suite](https://developer.nvidia.com/rapids) - popular libraries with GPU
- [NetworkX](https://networkx.org/) - new feature with fast backend like GraphBLAS and nx-cugraph 
- [copier](https://copier.readthedocs.io/en/stable/) - A library and CLI app for rendering project templates.
- [narwhals](https://github.com/narwhals-dev/narwhals) - DataFrame API connector. 
- [Polars](https://github.com/pola-rs/polars) - popular fast alternative to pandas. 

## Talks I Missed (and Want to Catch on YouTube)

With parallel sessions, there’s always FOMO — here are talks I missed but plan to catch up on when recordings are available:

- **Tutorial: Package Your Python Code as a CLI**
- **Why you should stop pretending your sparse data is dense**
- **How we unified feature engineering across data and backend at Monzo**
- **Enhancing Fraud Detection with LLM-Generated Profiles: From Analyst Efficiency to Model Performance**
- **Successful Projects through a bit of Rebellion**
- **CUDA in Python: A New Era for GPU Acceleration**
- **Is coding assistant as good as we thought in coding?**


## Knowledge or Tools Useful for My Current Work

What new knowledge, ideas, or tools from the conference I think will help with my day-to-day work:

- Polars: my team is already use it, but I don't have too much knowledge of it. It is time to learn. 
- Copier: it might solve the problem of cookiecutter is always a snapshot in time. 
- cuPy: investigate how cuPy/GPU can help improving performance. We need to access the cost of : GPU hardware, and man efforts to refactor existing code. 
- networkX: the new feature seems improves speed, but might be less relevant to my work's use case, which ues networkX but essentially a task graph (so time spending on network is very minimal, the computing in node is heavy)

## Conference Experience

Overall it's very good. It's the first time we use this venue (near St.Paul), and it was great. I heard a lot of praise of the venue. The food/snacks were amazingly good. 

Logistics are good. All 3 days for me were very long. I arrive before 8am, and talks runs to 5pm, then everyday there were social events. 

Teh community's vibe was great. Many people will hang out in the pubs and restaurant  after each day's talks. 


---

*Thanks to all the organisers, speakers, and community for an inspiring event! Looking forward to next year.*
