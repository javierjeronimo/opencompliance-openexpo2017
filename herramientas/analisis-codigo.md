
### Para análisis binario

- [Binary Analysis tool (BAT)](https://github.com/armijnhemel/binaryanalysis)
- [BinWalk](https://github.com/devttys0/binwalk)

**Muy buena, además, la explicación sobre análisis de archivos binarios que se incluye en la guía de "[practical GPL Compliance](https://linuxfoundation.org/news-media/research/practical-gpl-compliance)". Merece la pena echarle un vistazo en profundidad a esa guía. Pongo por aqui un resumen:

**Qué puede ser un binario:**
> - un ejecutable
> - un archivo objeto
> - un archivo de binarios
> - firmware
> - un desconocido conjunto de datos

Tienen en común:
> que no son código fuente
> que pueden ser construidos desde código opensource
> que deben ser analizados

Un archivo de código fuente debe inspeccionarse para encontrar binarios problemáticos en archivos de código fuente. Se debe buscar:
> - object files
> - módulos "out of tree" del kernel de linux
> - librerías y ejecutables
> - imágenes de file system
> - otras imágenes de firmware
> - realizar una reconstrucción del código fuente y comparlarlo con el binario original

¿He dicho ya que deberíais miraros la guía de "practical GPL"? :)


### Para análisis de código fuente
- [FOSSology](https://fossology.org)


En guía "[Open Source Compliance in the enterprise](http://go.linuxfoundation.org/open-source-compliance-ebook)" se mencionan muchas más herramientas de análisis de código que las que pongo aquí de ejemplo. 






