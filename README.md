# gh-action-build-info

This Action creates a build artefact file with info on the build.

## Inputs

### `output-location`

The path where the file should be created, defaults to `dist`.

### `artefact-filename`

The filename for the artefact, defaults to `_i` which will end up being `dist/_i.json`.

## Outputs

### `commit-difference-count`

The number of commits between the base branch and the secondary branch.

## Example usage

    - name: Get Commit Difference Count Between Two Branches
      id: doit
      uses: alliiiiiii/gh-action-build-info@v1.0.0
