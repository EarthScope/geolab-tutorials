# geolab-tutorials
Instructional Jupyter notebooks for working with EarthScope data and scientific workflows in the cloud.

## About

`geolab-tutorials` provides guided scientific workflows for developing practical research-computing skills in GeoLab.

The tutorials use authentic seismic, geodetic, and computational tasks to build skills that can transfer across datasets and research workflows. Rather than teaching users to reproduce a single notebook or processing pipeline, the pathways progress from accessing and exploring data to executing, adapting, and eventually scaling scientific workflows.

## Learning Pathways

### Seismic

The [`seismic/`](seismic/) pathway focuses on accessing, exploring, and analyzing seismic data in GeoLab.

Because seismic workflows can operate directly on waveform data in notebook-based environments, these notebooks emphasize data discovery and retrieval, data inspection and preparation, visualization, workflow execution, and analysis.

| Notebook | Description |
|---|---|
| [`01-discover-retrieve-seismic-data.ipynb`](seismic/01-discover-retrieve-seismic-data.ipynb) | Discover and retrieve seismic data. |
| [`02-inspect-prepare-seismic-data.ipynb`](seismic/02-inspect-prepare-seismic-data.ipynb) | Inspect and prepare seismic data for analysis. |
| [`03-running-a-scientific-workflow.ipynb`](seismic/03-running-a-scientific-workflow.ipynb) | Use prepared seismic data to run and evaluate a scientific workflow. |

### Geodetic

The [`geodetic/`](geodetic/) pathway focuses on accessing, exploring, and analyzing GNSS and other geodetic data and products in GeoLab.

These notebooks use the EarthScope SDK to work with GNSS observations, position streams, and satellite ephemerides directly in the cloud, rather than downloading and parsing raw data files (such as RINEX) locally. They emphasize data access and server-side filtering, quality inspection, visualization, and combining products for analysis.

| Notebook | Description |
|---|---|
| [`01-access-gnss-observations.ipynb`](geodetic/01-access-gnss-observations.ipynb) | Access GNSS observations using the EarthScope SDK. |
| [`02-explore-instantaneous-ppp-positions.ipynb`](geodetic/02-explore-instantaneous-ppp-positions.ipynb) | Retrieve and visualize high-rate PPP position streams and derived displacement. |
| [`03-inspect-prepare-gnss-observations.ipynb`](geodetic/03-inspect-prepare-gnss-observations.ipynb) | Retrieve, inspect, and prepare GNSS observations from multiple stations. |
| [`04-explore-satellite-geometry.ipynb`](geodetic/04-explore-satellite-geometry.ipynb) | Retrieve GNSS satellite positions and explore how satellite geometry relates to station observations. |

### Advanced Compute

The [`advanced-compute/`](advanced-compute/) pathway extends skills developed in the seismic and geodetic pathways to workflows with greater computational demands, including larger datasets, parallel and distributed execution, and resource scaling.

## Getting Started

These tutorials are designed to build on the operational skills introduced in **[Cloud Foundations](https://courses.earthscope.org)**. If you are new to GeoLab, completing Cloud Foundations first is recommended.

Clone the repository from a GeoLab terminal:

```bash
git clone https://github.com/EarthScope/geolab-tutorials.git
cd geolab-tutorials
```

Then choose the pathway most relevant to your work:

```text
seismic/
geodetic/
advanced-compute/
```

## Contributing

See CONTRIBUTING.md and the Instructional Notebook Design Guidelines for guidance on developing or revising notebooks. 
