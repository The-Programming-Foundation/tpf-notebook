# Notebook | The Programming Foundation

**Add any additional requirements as required to the `requirements.txt` file.**

_You can do this via the Github website by selecting the `requirements.txt` file, clicking to edit it, making the required changes then saving ("committing") the result to the `main` branch of your repository._

**Modify the contents of the `contents` folder to include the notebooks you want to distribute as part of your distribution.**

_You can do this by clicking on the `contents` directory and dragging notebooks from your desktop onto the contents listing. Wait for the files to be uploaded and then save them ("commit" them) to the `main` branch of the repository._

Check that you have Github Pages enabled for your repository: from your repository [_Settings_](./settings) tab, select the [_Pages_](./settings/pages) menu item and ensure that the source is set to `gh-pages`.

When you commit a file, an updated release will be built and published on the Github Pages site. Note that it may take a few minutes for the Github Pages site to be updated. Do a hard refresh on your Github Pages site in your web browser to see the new release.

### Further Information and Updates (JupyterLite)

For more info, keep an eye on the JupyterLite documentation:

- Configuring: https://jupyterlite.readthedocs.io/en/latest/configuring.html
- Deploying: https://jupyterlite.readthedocs.io/en/latest/deploying.html

## Development

Create a new environment:

```bash
mamba create -n jupyterlite-demo
conda activate jupyterlite-demo
pip install -r requirements.txt
```

Then follow the steps documented in the [Configuring](https://jupyterlite.readthedocs.io/en/latest/configuring.html) section.
