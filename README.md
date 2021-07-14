# configMapGenerator
To generate a ConfigMap from a file, add an entry to the files list in configMapGenerator. Here is an example of generating a ConfigMap with a data items from a test data files. You can inject multiple files with multiples ConfigMap.

- To apply this file via this command: kustomize build| kubectl apply -f -
- Note: Kustomization should be installed in your system `brew install kustomize
- https://kubectl.docs.kubernetes.io/installation/kustomize/homebrew/
`
