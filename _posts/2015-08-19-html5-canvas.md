---
layout: post
title:  html5 canvas
date:   2015-08-19 14:11 
categories: tech 
---

HTML5 canvas example

{% highlight javascript %}

        var mycanvas = document.createElement("canvas");
        mycanvas.id = "mycanvas";
        document.body.appendChild(mycanvas);

        var mycontext = mycanvas.getContext("2d");
        mycontext.beginPath();
        mycontext.moveTo(10, 10);
        mycontext.lineTo(35, 35);
        mycontext.strokeStyle = "#000";
        mycontext.stroke();
        mycontext.beginPath();
        mycontext.arc(35, 25, 10, 0, Math.PI * 2, true);

        mycontext.fillStyle = "#f00";
        mycontext.fill();


{% endhighlight %}
    
<script>
        var mycanvas = document.createElement("canvas");
        mycanvas.id = "mycanvas";
        document.body.appendChild(mycanvas);

        var mycontext = mycanvas.getContext("2d");
        mycontext.beginPath();
        mycontext.moveTo(10, 10);
        mycontext.lineTo(35, 35);
        mycontext.strokeStyle = "#000";
        mycontext.stroke();
        mycontext.beginPath();
        mycontext.arc(35, 25, 10, 0, Math.PI * 2, true);

        mycontext.fillStyle = "#f00";
        mycontext.fill();
 </script>
