---
layout: page
title: About
permalink: /about/
---


<p class="info" id="info">

</p>

<div class="icon_container">

    {% include icon.html alt="Version control." title="Git: Version control" src="/C_blog/assets/img/icons/git.png" size="64" %}
    {% include icon.html alt="Version control." title="Github: Version control" src="/C_blog/assets/img/icons/github.png" size="64" %}
    {% include icon.html alt="html" title="Html" src="/C_blog/assets/img/icons/html5.png" size="64" %}
    {% include icon.html alt="css" title="Css" src="/C_blog/assets/img/icons/css3.png" size="64" %}
    {% include icon.html alt="JavaScript." title="JavaScript " src="/C_blog/assets/img/icons/js.png" size="64" %}
    {% include icon.html alt="Databases." title="Databases " src="/C_blog/assets/img/icons/database.png" size="64" %}
    {% include icon.html alt="Jekyll." title="Jekyll Static site generator" src="/C_blog/assets/img/icons/jekyll_logo.png" size="64" %}
    {% include icon.html alt="Python." title="Python" src="/C_blog/assets/img/icons/python.png" size="64" %}
    {% include icon.html alt="Jupyter Notebook." title="Jupyter: Interactive runtime enviroment" src="/C_blog/assets/img/icons/jupyter.png" size="64" %}
    {% include icon.html alt="Pandas." title="Pandas: open source data analysis and manipulation tool" src="/C_blog/assets/img/icons/pandas.png" size="64" %}
    {% include icon.html alt="Matplotlib." title="Matplotlib: library for creating static, animated, and interactive visualizations in python" src="/C_blog/assets/img/icons/matplotlib.png" size="64" %}
    {% include icon.html alt="Node js." title="Node js: Runtime enviroment" src="/C_blog/assets/img/icons/node-js.png" size="64" %}
    {% include icon.html alt="React." title="React: Javascript library " src="/C_blog/assets/img/icons/react.png" size="64" %}
    {% include icon.html alt="Vue." title="Vue: Open source javascritp framework" src="/C_blog/assets/img/icons/vue.png" size="64" %}

</div>

<script>
    let paragraph = document.getElementById("info");
    const espa =`
    <button id="lang_change" class="lang_change" onClick="self.lang();">ENGLISH</button>
    <br>
    <br>
    Me llamo Carlos y me encanta la tecnologia, el desarrollo web y todo lo relacionado con los ordenadores.<br>
    Desde el back end y la integración hasta el front end y el desarrollo de interfaz y experiencia del usuario.<br>
    He preparado esta página para recoger y mostrar el contenido de algunos de mis repositorios en github.<br>
    <br>
    Algunos de los tópicos que me interesan:
    `;
    const engl=`
    <button id="lang_change" class="lang_change" onClick="self.lang();">ESPAÑOL</button>
    <br>
    <br>
    My name is Carlos and I love technology and everything computer related.<br>
    From back-end integration to front-end Ui and user experience design, and everything in between.<br>
    I´ve set this page to gather and show the content of some of my repositories in github.<br>
    <br>
    Some topics I´m interested in:
    </p>
    `;
    paragraph.innerHTML = espa;
    let esp = true;
    function lang(){
        if(esp){
            paragraph.innerHTML = engl;
            esp = false;
            // document.getElementById("start").firstChild.data="START";
        }else {
            paragraph.innerHTML = espa;
            esp = true;
            //document.getElementById("start").firstChild.data="EMPEZAR";
        }
    }
    function hide_title(){
        let titulo = document.getElementsByClassName("post-title");
        titulo[0].style.display = "none";
    }
    hide_title();
</script>
