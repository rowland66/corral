## Fix bundle scripts running during fetch of git repository

Corral was executing the bundle scripts while the git repository was being fetched. This was most noticable when downloading a bundle for the first time, as it was likely that the bundle file wasn't on disk when Corral tried to find the scripts to run.

The fix waits for the repository to be successfully fetched before executing the bundle scripts.

