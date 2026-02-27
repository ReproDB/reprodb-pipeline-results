# Artifact Analysis Results

This repository records the input, intermediate (cache), and output data from each pipeline run of [researchartifacts/artifact_analysis](https://github.com/researchartifacts/artifact_analysis).

Each commit represents a single pipeline run snapshot, allowing reproducible re-analysis based on the same underlying data.

## Structure

```
cache/              # HTTP and API response caches (namespaced)
output/
  _data/            # Generated YAML data files
  assets/
    data/           # Generated JSON data files
    charts/         # Generated SVG visualizations
input/
  dblp_checksum.txt # SHA-256 of the DBLP XML used
  pipeline_args.txt # Arguments passed to the pipeline
  pipeline.log      # Pipeline stdout/stderr
```

