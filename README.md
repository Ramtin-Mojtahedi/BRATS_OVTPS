# Multi-modal Brain Tumour Segmentation Using Transformer with Optimal Patch Size

This repository is intended to accompany the peer-reviewed BrainLes 2022 paper on optimal vision-transformer patch size for multi-modal brain-tumour segmentation.

<!-- repository-guide:start -->
## At a glance

[Peer-reviewed paper](https://doi.org/10.1007/978-3-031-33842-7_17) · [`CITATION.cff`](CITATION.cff)

### Package evidence

| Evidence source | Finding |
|---|---|
| Dependency manifests | None present |
| Source-code imports | None; no implementation is committed |
| Research data | BraTS 2021 data are not distributed here |

### Reproducibility boundary

This repository currently records publication and release-status metadata only. It has no executable preprocessing, model, training, inference, or evaluation artifacts; therefore, adding a software pipeline diagram would imply functionality that is not present. Use 2023 for the formal proceedings citation while retaining the BrainLes 2022 event context.
<!-- repository-guide:end -->

## Repository status

No implementation is included at present. This repository currently provides bibliographic and release-status information only; it does **not** contain source code, notebooks, model definitions, trained weights, preprocessing scripts, experiment configurations, software-environment files, split definitions, or research data. The paper’s results cannot be reproduced from this repository alone.

## Associated publication

Ramtin Mojtahedi, Mohammad Hamghalam, and Amber L. Simpson. “Multi-modal Brain Tumour Segmentation Using Transformer with Optimal Patch Size.” In *Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain Injuries (BrainLes 2022)*, Lecture Notes in Computer Science, vol. 13769, pp. 195–204. Springer, 2023.

- Publisher record and DOI: <https://doi.org/10.1007/978-3-031-33842-7_17>
- First author ORCID: <https://orcid.org/0000-0002-3953-3256>

The workshop took place in 2022, while the proceedings paper was published online on 18 July 2023. Use **2023** as the publication year in formal citations.

## Data and reproduction

The study uses Brain Tumor Segmentation (BraTS) 2021 data. No copy of that dataset is distributed here. Researchers should obtain the data through the provider’s current authorized access route and follow its registration, data-use, privacy, redistribution, and citation requirements.

Consult the paper for the reported methods and evaluation. A future reproducible implementation should provide exact data-version and access information, preprocessing and quality-control scripts, split definitions, a pinned environment, training and inference entry points, configurations and seeds, checkpoint provenance, and evaluation scripts with expected outputs.

Until those artifacts are released, please treat this repository only as a pointer to the publication. For artifact-availability questions, contact the author through the [Ramtin-Mojtahedi GitHub profile](https://github.com/Ramtin-Mojtahedi) or [ORCID record](https://orcid.org/0000-0002-3953-3256).

## Citation

Please cite the peer-reviewed paper:

```bibtex
@incollection{mojtahedi2023bratsovtps,
  author    = {Mojtahedi, Ramtin and Hamghalam, Mohammad and Simpson, Amber L.},
  title     = {Multi-modal Brain Tumour Segmentation Using Transformer with Optimal Patch Size},
  booktitle = {Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain Injuries},
  series    = {Lecture Notes in Computer Science},
  volume    = {13769},
  pages     = {195--204},
  publisher = {Springer Nature Switzerland},
  year      = {2023},
  doi       = {10.1007/978-3-031-33842-7_17},
  url       = {https://doi.org/10.1007/978-3-031-33842-7_17}
}
```

Machine-readable citation metadata is also provided in `CITATION.cff`.

## Rights and reuse

No `LICENSE` file or implementation is currently provided, and this README does not grant a software, data, or content license. Copyright and other rights remain with their respective holders. The paper and BraTS data are governed by their own terms.
