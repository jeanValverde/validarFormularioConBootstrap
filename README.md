# Validador de Formularios automáticos 


## Construido con 🛠️

_Este proyecto WEB contiene._

* [JavaScript](https://www.javascript.com/) 
* [Bootstrap](https://getbootstrap.com/) 

### Pre-requisitos 📋

* **HTML** 

## Comenzando 🚀

_Cada ID de los "< input id="idUnico />" deben ser únicos_

* Text
* Rut (Identificador chileno)
* Number
* Password (Solo registrar)
* Correo 
* File img 
* Radio
* Checkbox
* Text Area 
```
<script src="path/formularios.js"></script>
```

```
<script type="text/javascript" >

       var nameForm = document.getElementsByName("nameForm")[0];
       validatorForms(nameForm);
       
       var otherForm = document.getElementsByName("otherForm")[0];
       validatorForms(otherForm);
       
</script>
```

```
<input type="type" id="idUnico" class="form-control">
<div class="valid-feedback">
     Mensaje correcto 
</div>
<div class="invalid-feedback">
     Escribe el mensaje incorrecto.
</div>
```


Mira **Deployment** para conocer como desplegar el proyecto.


## Deployment 📦

_Para iniciar en producción usamos Zeit como una "CDN"_

```
<script src="https://validarformularioconbootstrap.jeanvalverde.now.sh/public_html/js/formularios.js"></script> 
```
```
https://validarformularioconbootstrap.jeanvalverde.now.sh/public_html/js/formularios.js
```


* [Zeit](https://www.zeit.co/)
* [CDN](https://validarformularioconbootstrap.jeanvalverde.now.sh/public_html/js/formularios.js)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/jeanValverde/validarFormularioConBootstrap/tags).

## Autores ✒️

* **Jean González** - *Trabajo Inicial* - [Jean González](https://github.com/jeanValverde)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/jeanValverde/validarFormularioConBootstrap/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Mira el archivo [LICENSE.md](LICENSE.md)

---
⌨️ con ❤️ por [Jean González](https://github.com/jeanValverde) 😊
