# MyMaven

My Maven

## Archetype

| Archetype ArtifactIds       | Description                                                   | Done |
| --------------------------- | ------------------------------------------------------------- | ---- |
| maven-archetype-archetype   | An archetype to generate a sample archetype.                  |      |
| maven-archetype-j2ee-simple | An archetype to generate a simplifed sample J2EE application. | ?    |
| maven-archetype-plugin      | An archetype to generate a sample Maven plugin.               |      |
| maven-archetype-plugin-site | An archetype to generate a sample Maven plugin site.          |      |
| maven-archetype-portlet     | An archetype to generate a sample JSR-268 Portlet.            |      |
| maven-archetype-quickstart  | An archetype to generate a sample Maven project.              | Y    |
| maven-archetype-simple      | An archetype to generate a simple Maven project.              |      |
| maven-archetype-site        | An archetype to generate a sample Maven site. *               |      |
| maven-archetype-site-simple | An archetype to generate a sample Maven site.                 |      |
| maven-archetype-site-skin   | An archetype to generate a sample Maven Site Skin.            |      |
| maven-archetype-webapp      | An archetype to generate a sample Maven Webapp project.       | Y    |

* An archetype to generate a sample Maven site which demonstrates some of the supported document types like APT, Markdown, XDoc, and FML and demonstrates how to i18n your site.

## Templates

```dos
mvn archetype:generate
```

Normally, we just use the following two templates :

* maven-archetype-webapp – Java Web Project (WAR)
* maven-archetype-quickstart – Java Project (JAR)
