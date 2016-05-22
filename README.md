# REPOEngine
This is the overall architecture for the OCDX Repository collection 

# Architecture
* Wikibase is used to create manifests, following the manifest laid out in libbyh/ocdx.  A sparkle engine will be used to search for the collections 
** Have wikibase be able to launch a notebook, including the full contents of the collection (defined below)
* JupyterHub is used, following a K8S architecure described in 
* Each collection contains:
** A Manifest
** A pointer to a dataset (could be multiple files)
** A Jupyter Hub Notebook Directory containing a set of notebooks 

## Wikibase
