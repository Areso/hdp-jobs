# hdp-jobs
Hadoop Jobs is a bunch of Jenkins Pipelines and Ansible Playbooks for building a specific version of Hadoop from source.  
1. Ordering a VM from a cloud provider (Digital Ocean)  
2. Update OS, install Docker  
3. Build Hadoop from the patched sources of the specific version  
4. Run built images as LDC/LXD containers, with building a network between them  
5. Put there file (through POST) and get the file back, just a smoke test
