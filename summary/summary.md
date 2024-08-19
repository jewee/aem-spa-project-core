<a id="top"></a>

<p style="font-size: 24px;"><img src="./qct-icons/transform-logo.svg" style="margin-right: 15px; vertical-align: middle;"></img><b>Code Transformation Summary by Amazon Q </b></p>
<p><img src="./qct-icons/transform-variables-dark.svg" style="margin-bottom: 1px; vertical-align: middle;"></img> Lines of code in your application: 1539 <p>
<p><img src="./qct-icons/transform-clock-dark.svg" style="margin-bottom: 1px; vertical-align: middle;"></img> Transformation duration: 40 min(s) <p>
<p><img src="./qct-icons/transform-dependencies-dark.svg" style="margin-bottom: 1px; vertical-align: middle;"></img> Planned dependencies replaced: 4 of 11 <p>
<p><img src="./qct-icons/transform-dependencyAnalyzer-dark.svg" style="margin-bottom: 1px; vertical-align: middle;"></img> Additional dependencies added: 27 <p>
<p><img src="./qct-icons/transform-smartStepInto-dark.svg" style="margin-bottom: 1px; vertical-align: middle;"></img> Planned deprecated code instances replaced: 0 of 0 <p>
<p><img src="./qct-icons/transform-listFiles-dark.svg" style="margin-bottom: 1px; vertical-align: middle;"></img> Files changed: 9 <p>
<p><img src="./qct-icons/transform-build-dark.svg" style="margin-bottom: 1px; vertical-align: middle;"></img> Build status in Java 17: <span style="color: #CCCC00">PARTIALLY_SUCCEEDED</span> <p>

### Table of Contents

1. <a href="#build-log-summary">Build log summary</a> 
1. <a href="#planned-dependencies-replaced">Planned dependencies replaced</a> 
1. <a href="#additional-dependencies-added">Additional dependencies added</a> 
1. <a href="#deprecated-code-replaced">Deprecated code replaced</a> 
1. <a href="#other-changes">Other changes</a> 
1. <a href="#all-files-changed">All files changed</a> 
1. <a href="#next-steps">Next steps</a> 


### Build log summary <a style="float:right; font-size: 14px;" href="#top">Scroll to top</a><a id="build-log-summary"></a>

Amazon Q could not build the upgraded code in Java 17. The following build log snippet that shows the errors Amazon Q encountered during the build log. To view the full build log, open [`buildCommandOutput.log`](./buildCommandOutput.log)

```
The Maven build failed while building the spa-project-core-core JAR module. The root cause was a missing dependency for com.adobe.aem:uber-jar:jar:apis:6.5.21 which could not be resolved. This caused the reactor build to fail at the spa-project-core-core module and skip building the subsequent content package modules.
```


### Planned dependencies replaced <a style="float:right; font-size: 14px;" href="#top">Scroll to top</a><a id="planned-dependencies-replaced"></a>

Amazon Q updated the following dependencies that it identified in the transformation plan

| Dependency | Action | Previous version in Java 8 | Current version in Java 17 |
|--------------|--------|--------|--------|
| `jakarta.inject:jakarta.inject-api` | Added | - | 2.0.1 |
| `jakarta.servlet:jakarta.servlet-api` | Added | - | 6.1.0 |
| `javax.servlet:javax.servlet-api` | Removed | - | - |
| `org.jacoco:jacoco-maven-plugin` | Updated | 0.8.5 | 0.8.12 |

### Additional dependencies added <a style="float:right; font-size: 14px;" href="#top">Scroll to top</a><a id="additional-dependencies-added"></a>

Amazon Q updated the following additional dependencies during the upgrade

| Dependency | Action | Previous version in Java 8 | Current version in Java 17 |
|--------------|--------|--------|--------|
| `com.adobe.aem:uber-jar` | Updated | 6.4.2 | 6.5.21 |
| `com.adobe.cq:core.wcm.components.all` | Updated | 2.15.0 | 2.25.4 |
| `com.adobe.cq:core.wcm.components.core` | Updated | 2.15.0 | 2.25.4 |
| `com.day.cq.wcm:cq-wcm-taglib` | Updated | 5.7.4 | 5.8.2 |
| `io.wcm:io.wcm.testing.aem-mock.junit5` | Updated | 2.5.2 | 5.5.2 |
| `javax.inject:javax.inject` | Updated | - | 1 |
| `javax.servlet.jsp:jsp-api` | Updated | 2.1 | 2.2 |
| `org.apache.maven.plugins:maven-release-plugin` | Updated | 2.5.3 | 3.1.0 |
| `org.apache.maven.plugins:maven-source-plugin` | Updated | 3.0.1 | 3.3.1 |
| `org.apache.sling:org.apache.sling.models.api` | Updated | 1.3.6 | 1.5.4 |
| `org.jetbrains:annotations` | Updated | 18.0.0 | - |
| `org.junit:junit-bom` | Updated | 5.4.1 | 5.10.3 |
| `org.mockito:mockito-core` | Updated | 2.25.1 | - |
| `org.mockito:mockito-junit-jupiter` | Updated | 2.25.1 | - |
| `org.osgi:org.osgi.annotation.bundle` | Updated | 1.0.0 | 2.0.0 |
| `org.osgi:org.osgi.annotation.versioning` | Updated | 1.1.0 | 1.1.2 |
| `org.osgi:org.osgi.framework` | Updated | 1.9.0 | 1.10.0 |
| `org.osgi:org.osgi.resource` | Updated | 1.0.0 | 1.0.1 |
| `org.osgi:org.osgi.service.cm` | Updated | 1.6.0 | 1.6.1 |
| `org.osgi:org.osgi.service.component` | Updated | 1.4.0 | 1.5.1 |
| `org.osgi:org.osgi.service.component.annotations` | Updated | 1.4.0 | 1.5.1 |
| `org.osgi:org.osgi.service.event` | Updated | 1.3.1 | 1.4.1 |
| `org.osgi:org.osgi.service.log` | Updated | 1.4.0 | 1.5.0 |
| `org.osgi:org.osgi.service.metatype.annotations` | Updated | 1.4.0 | 1.4.1 |
| `org.slf4j:slf4j-api` | Updated | 1.7.21 | 2.0.13 |
| `org.slf4j:slf4j-simple` | Updated | 1.7.25 | 2.0.13 |
| `uk.org.lidalia:slf4j-test` | Updated | 1.0.1 | 1.2.0 |

### Deprecated code replaced <a style="float:right; font-size: 14px;" href="#top">Scroll to top</a><a id="deprecated-code-replaced"></a>

Amazon Q replaced the following instances of deprecated code. An instance with 0 files
changed indicates Amazon Q wasn't able to replace the deprecated code.

| Deprecated code | Files changed |
|----------------|----------------|


### Other changes <a style="float:right; font-size: 14px;" href="#top">Scroll to top</a><a id="other-changes"></a>



### All files changed <a style="float:right; font-size: 14px;" href="#top">Scroll to top</a><a id="all-files-changed"></a>

| File | Action |
|----------------|--------|
| [.github/workflows/ci.yml](../.github/workflows/ci.yml) | Updated |
| [.github/workflows/maven-release.yml](../.github/workflows/maven-release.yml) | Updated |
| [all/pom.xml](../all/pom.xml) | Updated |
| [core/pom.xml](../core/pom.xml) | Updated |
| [core/src/main/java/com/adobe/aem/spa/project/core/internal/impl/PageImpl.java](../core/src/main/java/com/adobe/aem/spa/project/core/internal/impl/PageImpl.java) | Updated |
| [core/src/test/java/com/adobe/aem/spa/project/core/internal/impl/HierarchyComponentContextWrapperTest.java](../core/src/test/java/com/adobe/aem/spa/project/core/internal/impl/HierarchyComponentContextWrapperTest.java) | Updated |
| [core/src/test/java/com/adobe/aem/spa/project/core/internal/impl/utils/HierarchyUtilsTest.java](../core/src/test/java/com/adobe/aem/spa/project/core/internal/impl/utils/HierarchyUtilsTest.java) | Updated |
| [pom.xml](../pom.xml) | Updated |
| [ui.apps/pom.xml](../ui.apps/pom.xml) | Updated |

### Next steps <a style="float:right; font-size: 14px;" href="#top">Scroll to top</a><a id="next-steps"></a>

1. Please review and accept the code changes using the diff viewer.If you are using a Private Repository, please ensure that updated dependencies are available.
1. 
1. In order to successfully verify these changes on your machine, you will need to change your project to Java 17. We verified the changes using [Amazon Corretto Java 17](https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/what-is-corretto-17.html
) build environment.
1. If this project uses Maven CheckStyle, Enforcer, FindBugs or SpotBugs plugins, Q Code Transformation will disable those plugins when we build the project to verify proposed upgrades.