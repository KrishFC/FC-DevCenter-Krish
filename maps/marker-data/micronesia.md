---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: Micronesia

#### JavaScript Alias: maps/micronesia


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
    "data": [
        {
            "id": "FM.CH"
        },
        {
            "id": "FM.KO"
        },
        {
            "id": "FM.PO"
        },
        {
            "id": "FM.YA"
        }
    ],
    "markers": {
        "shapes": [
            {
                "id": "myCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,333333",
                "fillpattern": "radial",
                "showborder": "000000",
                "radius": "4"
            },
            {
                "id": "newCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,000099",
                "fillpattern": "radial",
                "showborder": "000000",
                "radius": "3"
            }
        ],
        "items": [
            {
                "id": "KO",
                "shapeid": "myCustomShape",
                "x": "592.6",
                "y": "142.31",
                "label": "Kolonia"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "35.73",
                "y": "60.84",
                "label": "Colonia"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "174.95",
                "y": "142.31",
                "label": "Agana"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "419.35",
                "y": "121.68",
                "label": "Moen"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape",
                "x": "732.85",
                "y": "181.5",
                "label": "Kosrae"
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
    "map": {
        "animation": "0",
        "showshadow": "0",
        "showmarkerlabels": "1",
        "fillcolor": "F1f1f1",
        "bordercolor": "999999",
        "basefont": "Verdana",
        "basefontsize": "10",
        "legendposition": "bottom",
        "usehovercolor": "1",
        "showmarkertooltip": "1"
    },
    "data": [
        {
            "id": "FM.CH"
        },
        {
            "id": "FM.KO"
        },
        {
            "id": "FM.PO"
        },
        {
            "id": "FM.YA"
        }
    ],
    "markers": {
        "shapes": [
            {
                "id": "myCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,333333",
                "fillpattern": "radial",
                "showborder": "000000",
                "radius": "4"
            },
            {
                "id": "newCustomShape",
                "type": "circle",
                "fillcolor": "FFFFFF,000099",
                "fillpattern": "radial",
                "showborder": "000000",
                "radius": "3"
            }
        ],
        "definition": [
            {
                "id": "KO",
                "x": "592.6",
                "y": "142.31",
                "label": "Kolonia"
            },
            {
                "id": "01",
                "x": "35.73",
                "y": "60.84",
                "label": "Colonia"
            },
            {
                "id": "02",
                "x": "174.95",
                "y": "142.31",
                "label": "Agana"
            },
            {
                "id": "03",
                "x": "419.35",
                "y": "121.68",
                "label": "Moen"
            },
            {
                "id": "04",
                "x": "732.85",
                "y": "181.5",
                "label": "Kosrae"
            }
        ],
        "application": [
            {
                "id": "KO",
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
