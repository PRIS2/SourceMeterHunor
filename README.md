<p align="center"><a><img src="https://www.sonarqube.org/assets/logo-31ad3115b1b4b120f3d1efd63e6b13ac9f1f89437f0cf6881cc4d8b5603a52b4.svg" align="center" width="600"></a></p>

# SourceMeterHunor - SonarQube

Para esta práctica he empleado 3 versiones de SonarQube:

- [8.9.7.52159](https://github.com/SonarSource/sonarqube/releases/tag/8.9.7.52159)
- [9.2.4.50792](https://github.com/SonarSource/sonarqube/releases/tag/9.2.4.50792)
- [9.3.0.51899](https://github.com/SonarSource/sonarqube/releases/tag/9.3.0.51899)

## Uso de SourceMeter

Ejecutar el siguiente comando para analizar el código fuente de un sistema de software.
```bash
  SourceMeterJava -projectName=MyProject -projectBaseDir=MyProjectDir -resultsDir=Results -runFB=true -FBFileList=filelist.txt
```
## Resultados
Dentro del directorio resultados se encuentran los 3 archivos .csv necesarios.

Los resultados, completos, obtenidos tienen un tamaño en disco superior al permitido por Github, que no permite archivos de más de 100Mb.
Como alternativa dejo los resultados en una carpeta compartida donde se pueden ver los resultados.


[Resultados SourceMeter](https://drive.google.com/drive/folders/1tB5J00JzF-7AwgCR4K05E00r53LA3WtT?usp=sharing)

