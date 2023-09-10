# Frontend Mentor - solution de QR code component 

Esta es una solución para [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Los desafíos de Frontend Mentor te ayudan a mejorar tus habilidad en la creación de código mediante proyectos realistas. 

## Tabla de contenidos 

- [Resumen](#Resumen)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Mi proceso](#mi-proceso)
  - [Construido con](#construido-con)
  - [Lo que puse en práctica](#lo-que-puse-en-practica)
- [Autor](#autor)

## Resumen

El desafío consiste en construir un componente de código QR que se asemeje los más posible al diseño entregado.

Para este desafío se uso solo html y css nativos para prácticar los conceptos básicos.

### Screenshot

![](./images/Screenshot%202023-09-10%20at%2019-24-24%20Frontend%20Mentor%20QR%20code%20component.png)

### Links

- URL de la Solución: [Link a la solución](https://github.com/dariomiguel/FrontendMentor-QRCodeComponent)
- URL del sitio: [Link al sitio](https://frontend-mentor-qr-code-component-ruddy.vercel.app/)

## Mi proceso

### Construido con

- Lenguaje HTML5 semántico
- Propiedades personalizadas de CSS

### Lo que puse en practica

Está práctica me sirvio para repasar las bases de css que ya no estaba utilizando tanto pero que pueden llegar a ser muy importantes como:

El link de las fuentes se coloca en el head del html:

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap">
```
Los pasos básicos en css como el reseteo del formato y centrar un elemento contenedor

```css
*{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
    font-family: 'Outfit', sans-serif;
}

.textContainer{
    width: 288px;
    height: 129px;
    margin: 0 auto;
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 16px;
}
```

## Autor

- GitHub - [dariomiguel](https://github.com/dariomiguel)
- Frontend Mentor - [@dariomiguel](https://www.frontendmentor.io/profile/dariomiguel)
