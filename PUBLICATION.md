# Publication record

Copied into `madhurag123/spendmap` on 2026-10-09 at the owner's request. Original source repositories and remotes were not changed. Existing commit authors, copyright notices, data provenance and third-party licenses are retained; a repository copy does not transfer authorship.

- Source: https://github.com/abhijith-abhii/spendmap
- Source revision: `22421997467be37172b9bef3f4c00b6f77abf935`
- Implementation status: implemented; recorded checks passed.
- Publication checks: Local automated checks passed on 2026-10-09. Scope: see the recorded check command and output below.
- This upload does not deploy cloud infrastructure or enable paid integrations.

## Evidence and limitations

Existing screenshots, sample outputs and test reports describe the original implementation and the dates recorded in those files. Links to original CI runs deliberately retain their original account because those runs happened there. They are not claims of new destination-account CI results. Follow the README for installation, dependencies, sample data and limitations. Any new CI results are available in this repository's Actions tab.

Development used substantial AI assistance. Present the work as a project you can run and explain, with its retained provenance, rather than employment experience or verified production adoption.

## Publication check record

```text
..........                                                               [100%]
=============================== warnings summary ===============================
tests/test_spend.py::test_category_reconciliation
  <workspace>/work/clean-envs/spendmap/lib/python3.12/site-packages/joblib/externals/loky/backend/context.py:136: UserWarning: Could not find the number of physical cores for the following reason:
  invalid literal for int() with base 10: ''
  Returning the number of logical cores instead. You can silence this warning by setting LOKY_MAX_CPU_COUNT to the number of cores you want to use.
    warnings.warn(

-- Docs: https://docs.pytest.org/en/stable/how-to/capture-warnings.html
10 passed, 1 warning in 2.36s


```
