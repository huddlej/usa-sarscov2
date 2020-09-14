# usa-sarscov2

Prototype of state- and territory-level SARS-CoV-2 Nextstrain builds for the United States.
**Note: Do not use these to make any scientific conclusions!**

## Usage

Choose a top-level working directory for your analyses.
Clone the Nextstrain ncov repository into that top-level directory.

```bash
git clone https://github.com/nextstrain/ncov.git
```

Clone this repository into the same top-level directory.

```bash
git clone https://github.com/huddlej/usa-sarscov2.git
```

Change into the `ncov` directory.

```bash
cd ncov/
```

Run the workflow on a SLURM cluster.

```bash
snakemake --profile ../usa-sarscov2/profiles/usa/
```

View the resulting builds with auspice from a local machine.

```bash
auspice view
```
