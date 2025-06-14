---
title: Interactive Dashboard - Using ArcGIS - Perth Metropolitan Bike Usage Dashboard
summary: This project enhances a dashboard that analyzes bike usage patterns in Perth’s CBD to support transport planning and mode sharing. It identifies high-traffic areas, peak usage times, and infrastructure gaps, using speed data and visual insights. The initiative also encourages community engagement and promotes a stronger bike-riding culture.
date: 2023-10-24
type: docs
math: false
tags:
  - ArcGIS
  - Data Analytics
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

This [Dashboard](https://www.arcgis.com/apps/dashboards/c3a533e545db46029d817b9cbafdb8a1) was part of my Master’s final capstone project, where I collaborated closely with an industry partner to augment a dashboard designed to analyze bike usage patterns in Perth’s CBD. The dashboard supports data-driven decisions by identifying peak usage periods, high-traffic areas, and infrastructure gaps to improve transport planning and encourage mode sharing.

# *Embed videos, podcasts, code, LaTeX math, and even test students!**

# On this page, you'll find some examples of the types of technical content that can be rendered with Hugo Blox.

# Video

# Teach your course by sharing videos with your students. Choose from one of the following approaches:

# {{< youtube D2vj0WcvH5c >}}

# **Youtube**:

    {{</* youtube w7Ft2ymGmfc */>}}

# **Bilibili**:

    {{</* bilibili id="BV1WV4y1r7DF" */>}}

# **Video file**

# Videos may be added to a page by either placing them in your `assets/media/` media library or in your [page's folder](https://gohugo.io/content-management/page-bundles/), and then embedding them with the _video_ shortcode:

    {{</* video src="my_video.mp4" controls="yes" */>}}

# Podcast

# You can add a podcast or music to a page by placing the MP3 file in the page's folder or the media library folder and then embedding the audio on your page with the _audio_ shortcode:

    {{</* audio src="ambient-piano.mp3" */>}}

# Try it out:

# {{< audio src="ambient-piano.mp3" >}}

# Test students

# Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

# ```markdown
# {{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
# {{</* /spoiler */>}}
# ```

# renders as

# {{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

# Math

# Hugo Blox Builder supports a Markdown extension for $\LaTeX$ math. You can enable this feature by toggling the `math` option in your `config/_default/params.yaml` file.

# To render _inline_ or _block_ math, wrap your LaTeX math with `{{</* math */>}}$...${{</* /math */>}}` or `{{</* math */>}}$$...$${{</* /math */>}}`, respectively.

# {{% callout note %}}
# We wrap the LaTeX math in the Hugo Blox _math_ shortcode to prevent Hugo rendering our math as Markdown.
# {{% /callout %}}

# Example **math block**:

# ```latex
# {{</* math */>}}
# $$
# \gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
# $$
# {{</* /math */>}}
# ```

# renders as

# {{< math >}}
# $$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$
# {{< /math >}}

# Example **inline math** `{{</* math */>}}$\nabla F(\mathbf{x}_{n})${{</* /math */>}}` renders as {{< math >}}$\nabla F(\mathbf{x}_{n})${{< /math >}}.

# Example **multi-line math** using the math linebreak (`\\`):

# ```latex
# {{</* math */>}}
# $$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
# 1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
# {{</* /math */>}}
# ```

# renders as

# {{< math >}}

# $$
# f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
# 1-p_{0}^{*} & \text{if }k=0.\end{cases}
# $$

# {{< /math >}}

# Code

# Hugo Blox Builder utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    # ```python
    # import pandas as pd
    # data = pd.read_csv("data.csv")
    # data.head()
    # ```

# renders as

# ```python
# import pandas as pd
# data = pd.read_csv("data.csv")
# data.head()
# ```

# ## Inline Images

# ```go
# {{</* icon name="python" */>}} Python
# ```

# renders as

# {{< icon name="python" >}} Python

# Did you find this page helpful? Consider sharing it 🙌
