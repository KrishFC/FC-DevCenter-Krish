---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: Estonia

#### JavaScript Alias: maps/estonia


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
                "id": "TA",
                "shapeid": "myCustomShape",
                "x": "273.46",
                "y": "48.23",
                "label": "Tallinn",
                "labelpos": "right"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "220.09",
                "y": "67.73",
                "label": "Paldiski",
                "labelpos": "right"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "169.8",
                "y": "141.63",
                "label": "Haapsalu",
                "labelpos": "right"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "258.06",
                "y": "232.97",
                "label": "Parnu"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape",
                "x": "286.8",
                "y": "182.68",
                "label": "Vohma",
                "labelpos": "right"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape",
                "x": "437.67",
                "y": "227.84",
                "label": "Tartu"
            },
            {
                "id": "06",
                "shapeid": "newCustomShape",
                "x": "405.85",
                "y": "325.34",
                "label": "Valga",
                "labelpos": "right"
            },
            {
                "id": "07",
                "shapeid": "newCustomShape",
                "x": "503.35",
                "y": "52.34",
                "label": "Kohtla-Jarve"
            },
            {
                "id": "08",
                "shapeid": "newCustomShape",
                "x": "585.46",
                "y": "54.39",
                "label": "Narva",
                "labelpos": "left"
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
                "id": "TA",
                "x": "273.46",
                "y": "48.23",
                "label": "Tallinn",
                "labelpos": "right"
            },
            {
                "id": "01",
                "x": "220.09",
                "y": "67.73",
                "label": "Paldiski",
                "labelpos": "right"
            },
            {
                "id": "02",
                "x": "169.8",
                "y": "141.63",
                "label": "Haapsalu",
                "labelpos": "right"
            },
            {
                "id": "03",
                "x": "258.06",
                "y": "232.97",
                "label": "Parnu"
            },
            {
                "id": "04",
                "x": "286.8",
                "y": "182.68",
                "label": "Vohma",
                "labelpos": "right"
            },
            {
                "id": "05",
                "x": "437.67",
                "y": "227.84",
                "label": "Tartu"
            },
            {
                "id": "06",
                "x": "405.85",
                "y": "325.34",
                "label": "Valga",
                "labelpos": "right"
            },
            {
                "id": "07",
                "x": "503.35",
                "y": "52.34",
                "label": "Kohtla-Jarve"
            },
            {
                "id": "08",
                "x": "585.46",
                "y": "54.39",
                "label": "Narva",
                "labelpos": "left"
            }
        ],
        "application": [
            {
                "id": "TA",
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
            },
            {
                "id": "06",
                "shapeid": "newCustomShape"
            },
            {
                "id": "07",
                "shapeid": "newCustomShape"
            },
            {
                "id": "08",
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
