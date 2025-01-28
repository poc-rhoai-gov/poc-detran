`project_tag` is needed?


modded agnosticg 



### Questions

- Do I really need showcase-templates.yaml? Or should I just edit the location resource on OpenShift deployment?



### Notes

#### Devfile
WorkSpaces are triggered by accessing the URL of the workspace. This URL is defined in the catalog-info.yaml file that points to the repo created by the ArgoCD that contains the devfile.yaml.

---

Milestone 1:

- clean template.yaml - DONE
- adapt showcase-templates.yaml - DONE
- clean ./skeleton - DONE
- adapt ./manifest.yaml - DONE

Milestone 2:

- ArgoCD Configs
    - build helm
    - app helm
    - ai helm