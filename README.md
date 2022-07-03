# abics2-singularity
abICS environment on Singularity
[abics](https://github.com/issp-center-dev/abICS)実行環境のSingularityコンテナ化を目指すリポジトリです．

# How to build
`sudo singularity build abics2-singularity.sif abics2-singularity.def`

# How to use the container
`singularity exec abics2-singularity.sif (command)`
* インストール先
    ‐ qe: `/opt/q-e-qe-7.0`
    - SSSP(pseudopotentials): `/opt/SSSP_efficiency_pseudos`
    - aenet: `/opt/aenet/aenet-2.0.4`

# Notes
* 使用しているソフトウェアのライセンスついては，各々に準拠します