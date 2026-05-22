# The Path to Sustainability: Santa Clara University's Waste Diversion Journey

> An interactive data visualization exploring how SCU's waste management evolved from 2005 to 2023 — from a landfill-dependent system to a multi-stream diversion program achieving 68%+ diversion rates.
>
> **Live Site:** [khushiatcode.github.io/scu-waste-diversion](https://khushiatcode.github.io/scu-waste-diversion/)
>
> **Course Project | Santa Clara University | Data Visualization**
>
> ---
>
> ## Overview
>
> In 2005, Santa Clara University sent over 2.5 million pounds of waste to landfill annually, with a diversion rate of just 16.8%. By 2023, that diversion rate exceeded 68% — a 305% improvement — and 33.6 million pounds of waste had been diverted from landfill since the program began.
>
> This project tells that story through interactive data visualizations, surfacing the milestones, programs, and behavioral shifts that drove one of the most significant sustainability transformations in the university's history.
>
> ---
>
> ## Impact Numbers at a Glance
>
> | Metric | Value |
> |---|---|
> | Total waste diverted since 2005 | **33.6 million lbs** |
> | Current diversion rate (2023) | **68.1%** |
> | Improvement in diversion rate | **305%** |
> | Diversion rate in 2005 (baseline) | 16.8% |
> | Peak diversion rate achieved | **76.4% (2016)** |
>
> ---
>
> ## Visualizations
>
> ### 1. Waste Composition Over Time (2005–2023)
> An interactive stacked area chart showing the evolution of four waste streams — Landfill, Recycle, Compost, and Reuse — year by year. Includes:
> - Toggle visibility of individual waste categories via legend
> - - Drag-to-zoom on the timeline to inspect specific years
>   - - Highlights the dramatic shift in composition after composting launched in 2010
>    
>     - ### 2. Diversion Rate Progress
>     - A line chart tracking SCU's annual diversion rate from 2005 to 2023, annotated with the inflection point after 2010 when the composting program launched. Shows the clear step-change that targeted initiatives can produce.
>    
>     - ### 3. Seasonal Waste Generation Heatmap
>     - A month-by-category heatmap revealing seasonal patterns in waste generation, including:
>     - - **Summer spike**: May–August sees higher waste due to student move-out, campus renovations, summer programs, and bookstore operations
> - **Academic year patterns**: Correlates waste intensity with the university calendar
> - - Covers four waste categories: Landfill, Recycle, Compost, and Yardwaste
>  
>   - ### 4. Key Milestones Timeline
>   - Annotated program milestones overlaid on the data narrative:
>  
>   - | Year | Milestone |
>   - |------|----------|
>   - | 2010 | First campus-wide composting program launched |
>   - | 2012 | Composting expands 434% (192K → 1.03M lbs/year); diversion jumps 22.9% → 51.9% in one year |
>   - | 2015 | Food Recovery Network introduced; edible food diverted to hunger relief |
>   - | 2016 | Enhanced food scraps & yard waste collection; diversion rate peaks at 76.4% |
>
>   - ---
>
> ## Key Findings
>
> - **Composting was the turning point.** The 2012 expansion of composting drove the single largest year-over-year improvement in the dataset, demonstrating that targeted organics diversion has outsized impact.
> - - **Programs compound over time.** Each new stream (recycling, composting, reuse) added incrementally to the diversion rate, with effects that compounded as programs matured.
>   - - **Seasonality is structurally driven.** The summer waste spike is not random — it reflects identifiable operational factors (move-outs, renovations, camps) that can be planned for and mitigated.
>     - - **Decline from peak is a signal.** The diversion rate fell from its 2016 peak of 76.4% to 68.1% by 2023, suggesting an opportunity to analyze which programs lost momentum and why.
>      
>       - ---
>
> ## Tech Stack
>
> | Layer | Tools |
> |---|---|
> | Visualization | D3.js, custom SVG charts |
> | Styling | CSS3, responsive layout |
> | Frontend | HTML5, Vanilla JavaScript |
> | Deployment | GitHub Pages |
>
> ---
>
> ## Repository Structure
>
> ```
> scu-waste-diversion/
> ├── index.html       # Full interactive visualization site
> └── .github/
>     └── workflows/   # GitHub Pages deployment workflow
> ```
>
> ---
>
> ## Data Source
>
> Waste generation and diversion data sourced from **Santa Clara University Facilities** annual sustainability reporting (2005–2023). Data covers four waste streams: Landfill, Recycle, Compost, and Reuse, tracked by weight (pounds) and month.
>
> ---
>
> ## Author
>
> Built by [khushiatcode](https://github.com/khushiatcode) — Khushi Savaliya, MS CSE @ Santa Clara University
>
> ---
>
> ## License
>
> MIT License
> 
