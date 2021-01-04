# mstpylib

## Installing
Explicitly:
   ```
   pip install mstpylib --extra-index-url https://git.mst.edu/api/v4/projects/4927/packages/pypi/simple
   ```
Implicitly, add the following line to requirements.txt:
   ```
   mstpylib --extra-index-url https://git.mst.edu/api/v4/projects/4927/packages/pypi/simple
   ```

Unfortunately we'll have to explicitly list the project_id integer until we can come up with a workaround. GitLab supplies a [project_aliases endpoint](https://docs.gitlab.com/ee/api/project_aliases.html), but unfortunately only for the premium version.
