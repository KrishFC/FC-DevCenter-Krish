---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: Bosnia-Herzegovina

#### JavaScript Alias: maps/bosniaherzegovina


<div class="code-wrapper">
<ul class='code-tabs'>
    <li class='active'>
        <a data-toggle='new-json'>New JSON Format</a>
    </li>
    <li>
        <a data-toggle='old-json'>Old JSON Format</a>
    </li>
</ul>
<div class='tab-content'>
    
<div class='tab new-json-tab active'>
<pre><code class="language-json">
{
    "map": {
        "showshadow": "0",
        "showlabels": "0",
        "showmarkerlabels": "1",
        "fillcolor": "F1f1f1",
        "bordercolor": "CCCCCC",
        "basefont": "Verdana",
        "basefontsize": "10",
        "markerbordercolor": "000000",
        "markerbgcolor": "FF5904",
        "markerradius": "6",
        "usehovercolor": "0",
        "hoveronempty": "0",
        "showmarkertooltip": "1",
        "canvasBorderColor": "375277",
        "canvasBorderAlpha": "0"
    },
    "markers": {
        "shapes": [
            {
                "id": "myCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,333333",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "4"
            },
            {
                "id": "newCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,000099",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "3"
            }
        ],
        "items": [
            {
                "id": "SJ",
                "shapeid": "myCustomShape",
                "x": "321.71",
                "y": "266.77",
                "label": "Sarajevo",
                "labelpos": "left"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "15.73",
                "y": "82.75",
                "label": "Bihac",
                "labelpos": "right"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "224.8",
                "y": "350.62",
                "label": "Mostar"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "401.2",
                "y": "299.44",
                "label": "Gorazde",
                "labelpos": "right"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape",
                "x": "273.8",
                "y": "213.42",
                "label": "Zenica"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape",
                "x": "357.64",
                "y": "156.79",
                "label": "Tuzla"
            }
        ]
    }
}
</code><button class='btn btn-outline-secondary btn-copy' title='Copy to clipboard'>COPY</button>
</pre>


<p class='text-success'>New JSON format for map marker data.</p>

</div>
<div class='tab old-json-tab'>
<pre><code class="language-json">
{
    "map": {},
    "markers": {
        "shapes": [
            {
                "id": "myCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,333333",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "4"
            },
            {
                "id": "newCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,000099",
                "fillpattern": "radial",
                "showborder": "0",
                "radius": "3"
            }
        ],
        "definition": [
            {
                "id": "SJ",
                "x": "321.71",
                "y": "266.77",
                "label": "Sarajevo",
                "labelpos": "left"
            },
            {
                "id": "01",
                "x": "15.73",
                "y": "82.75",
                "label": "Bihac",
                "labelpos": "right"
            },
            {
                "id": "02",
                "x": "224.8",
                "y": "350.62",
                "label": "Mostar"
            },
            {
                "id": "03",
                "x": "401.2",
                "y": "299.44",
                "label": "Gorazde",
                "labelpos": "right"
            },
            {
                "id": "04",
                "x": "273.8",
                "y": "213.42",
                "label": "Zenica"
            },
            {
                "id": "05",
                "x": "357.64",
                "y": "156.79",
                "label": "Tuzla"
            }
        ],
        "application": [
            {
                "id": "SJ",
                "shapeid": "myCustomShape"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape"
            }
        ]
    }
}
</code><button class='btn btn-outline-secondary btn-copy' title='Copy to clipboard'>COPY</button>
</pre>


<p class='text-success'>Old JSON format for map marker data, using separate application and definition blocks.</p>

</div>
    
</div>
</div>
