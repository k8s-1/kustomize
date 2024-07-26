kustomize build .

https://kubectl.docs.kubernetes.io/guides/example/multi_base/

1. kustomize builds the resources from the kustomize file
2. kustomize can 'patch' resources
    - existing values won't be overridden
    - patching is rather inflexible, not as good as helm for large projects

