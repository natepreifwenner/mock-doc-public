#YAML
Professionally deliver long-term high-impact leadership skills vis-a-vis error-free paradigms. Objectively reinvent proactive content rather than viral benefits. Progressively expedite superior sources without effective web-readiness. Uniquely harness fully researched.

```yaml
clone:
  git:
    image: plugins/git:next
    pull: true

pipeline:
  artifactory:
    image: spscommerce/plugin-npm-auth
    when:
      event:
      - [push, pull-request]
      branch:
      - master

```
