# Setup Eigen3 docker action

Set up your GitHub Actions workflow with a specific version of the Eigen3

## Inputs

## `version`

**Required** Version of eigen. Default `latest`.

## Example usage

```yml
      - name: Install Eigen3
        uses: kupns-aka-kupa/setup-eigen3@v1
        with:
          version: 3.4.0
```
