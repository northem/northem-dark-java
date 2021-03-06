<img align="center" src="https://raw.githubusercontent.com/arcticicestudio/northem-dark-java/develop/src/main/assets/media/northem-dark-java-banner.png" alt="Northem Dark Java"/> <a href="https://github.com/arcticicestudio/northem-dark"><img align="right" src="https://raw.githubusercontent.com/arcticicestudio/northem-dark-java/develop/src/main/assets/media/northem-logo.png"/></a>

## 0.2.0 (2016-08-03) - Apache Maven Migration
This version is mainly focused on a [Apache Maven](https://maven.apache.org) migration.
Release and snapshot versions are now deployed to the [Central Repository](https://search.maven.org) via [OSS Sonatype](https://oss.sonatype.org).

### Improvements
#### Build Tool
  - Migrated to [Apache Maven](https://maven.apache.org) based on the [`glacier-apache-maven@0.3.0`](https://github.com/arcticicestudio/glacier-apache-maven) project skeletons

#### Documentation
  - The `README` has been modernized and now includes a "Getting started" section

## 0.1.0 (2016-04-09)
### Features
  - Implemented the [Northem Dark](https://github.com/arcticicestudio/northem-dark) color palette enumeration class [`NorthemDark`](https://github.com/arcticicestudio/northem-dark-java/blob/master/src/main/java/com/arcticicestudio/northem/NorthemDark.java)  

**Constants**

| Name           | RGB Value     |
| -------------- | ------------- |
| `DARKEST_COAL` | `31,31,35`    |
| `DARK_COAL`    | `36,36,41`    |
| `COAL`         | `41,41,46`    |
| `LIGHT_COAL`   | `79,79,89`    |
| `DIRTY_WHITE`  | `222,222,222` |
| `WHITE`        | `236,238,239` |
| `AQUA`         | `143,206,200` |
| `LIGHT_BLUE`   | `133,193,211` |
| `BLUE`         | `135,178,206` |
| `DARK_BLUE`    | `91,129,175`  |
| `RED`          | `224,116,115` |
| `YELLOW`       | `253,206,132` |
| `ORANGE`       | `240,160,111` |
| `LIME`         | `201,204,120` |
| `PURPLE`       | `194,161,202` |

**Methods**

| Name | Description |
| ---- | ----------- |
| `NorthemDark(final int RED, final int GREEN, final int BLUE)` | Constructs a new color object. |
| `public static String rgb(final Color COLOR)` | Converts the color to the RGB identifier. |
| `public static String hex(final Color COLOR)` | Converts the color to the HEX identifier. |
| `public Color get()` | Returns the color object. |

## 0.0.0 (2016-04-09) - Repository Reinitialization
