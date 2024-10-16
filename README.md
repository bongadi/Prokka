# Prokka

#### 5. Annotation
- **Why Perform Annotation?**: Genome annotation helps identify the biological features (e.g., genes, regulatory regions) within the assembled genome. Annotation assigns functional information to the genomic sequence, making it useful for further biological interpretation.
- **Tool**: Prokka (bacterial genome annotation)
  - **Installation**:
    ```bash
    conda install -c bioconda prokka
    ```
  - **Usage**:
    ```bash
    prokka --outdir output_dir --prefix annotation genome.fasta
    ```
