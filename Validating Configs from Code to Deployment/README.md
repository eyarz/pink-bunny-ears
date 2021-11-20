# Validating Configs from Code to Deployment ([presentation](https://github.com/eyarz/pink-bunny-ears/blob/07d47a06db1d7d52455548f961c699ce1c625332/Validating%20Configs%20from%20Code%20to%20Deployment/Validating%20Configs%20from%20Code%20to%20Deployment.pdf))

With great power comes great responsibility. While GitOps empowers your engineering organization with greater ownership - it can also have the downsides of being dangerous, if not properly managed and configured, as ultimately every engineer can impact production.

In this talk, we will go over some best practices when applying GitOps in your engineering organization, and ways to automate the validation of Infrastructure as Code config files, in order to build stability inherently into your GitOps practices.

[**WTF is Cloud Native? Conference**](https://www.youtube.com/watch?v=m1hReRl7fDk)  

## Resources from the presentation

### Valid file

⚙️ [yq - a portable command-line YAML processor](https://github.com/mikefarah/yq)

### Valid schema

🏪 [JSON Schema Store](https://www.schemastore.org/json/)  
🐍 [jsonschema (py)](https://python-jsonschema.readthedocs.io/en/stable/)  
📚 [Why you need to use Kubernetes schema validation tools](https://opensource.com/article/21/7/kubernetes-schema-validation)  

### Following best practices

📑 [A curated list of static analysis (SAST) tools for config files (and more)](https://github.com/analysis-tools-dev/static-analysis)
