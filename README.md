# Deployment workflows
Deze repo bevat herbruikbare Github workflows. Je kunt ze als volgt gebruiken in je workflow yaml bestand:

```
jobs:
  deploy:
    uses: Agrio-Uitgeverij/deployment-workflows/.github/workflows/deploy-processwire.yaml@main
```

De deploy-processwire.yaml workflow is bedoeld voor de Sterke Erven portal, maar zou in theorie ook werken voor andere ProcessWire sites
die bij dezelfde webhost worden gehost.

**Omdat dit een private repo is in de Agrio-Uitgeverij organisatie, moeten de workflows die deze repo gebruiken onderdeel zijn van
dezelfde organisatie.**