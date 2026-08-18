# geolab-tutorials
Instructional Jupyter notebooks for working with EarthScope data and scientific workflows in the cloud.

## About

`geolab-tutorials` provides guided scientific workflows for developing practical research-computing skills in GeoLab.

The tutorials use authentic seismic, geodetic, and computational tasks to build skills that can transfer across datasets and research workflows. Rather than teaching users to reproduce a single notebook or processing pipeline, the pathways progress from accessing and exploring data to executing, adapting, and eventually scaling scientific workflows.

## Learning Pathways

### Seismic

The [`seismic/`](seismic/) pathway focuses on accessing, exploring, and analyzing seismic data in GeoLab.

Because seismic workflows can operate directly on waveform data in notebook-based environments, these notebooks emphasize data discovery and retrieval, data inspection and preparation, visualization, workflow execution, and analysis.

See [`seismic/README.md`](seismic/README.md) for available notebooks, prerequisites, and recommended sequencing.

### Geodetic

The [`geodetic/`](geodetic/) pathway focuses on accessing, exploring, and analyzing GNSS and other geodetic data and products in GeoLab.

These notebooks use the EarthScope SDK to work with GNSS observations, position streams, and satellite ephemerides directly in the cloud, rather than downloading and parsing raw data files (such as RINEX) locally. They emphasize data access and server-side filtering, quality inspection, visualization, and combining products for analysis.

See [`geodetic/README.md`](geodetic/README.md) for available notebooks, prerequisites, and recommended sequencing.

### Advanced Compute

The [`advanced-compute/`](advanced-compute/) pathway extends skills developed in the seismic and geodetic pathways to workflows with greater computational demands, including larger datasets, parallel and distributed execution, and resource scaling.

See [`advanced-compute/README.md`](advanced-compute/README.md) for available materials.

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
