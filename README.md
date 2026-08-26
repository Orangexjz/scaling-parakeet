# RSA-512 Factorization

Automated RSA-512 factorization using CADO-NFS on GitHub Actions (free compute).

## Target

```
n = 10024736378350098430227678016352798779292618882528367487303651597605344143601617599298224756928363135181060229840615610442456500936388901255076451726534989
```

## Method

CADO-NFS (General Number Field Sieve) with 3 parallel GitHub Actions runners.
Each runner has 2 CPU cores and 7GB RAM. Runs resume automatically via cache.

## Status

Check the Actions tab for run progress.