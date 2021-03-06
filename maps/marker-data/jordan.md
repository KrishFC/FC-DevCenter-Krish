---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: Jordan

#### JavaScript Alias: maps/jordan


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
            "id": "JO.AJ"
        },
        {
            "id": "JO.AM"
        },
        {
            "id": "JO.AQ"
        },
        {
            "id": "JO.MA"
        },
        {
            "id": "JO.AT"
        },
        {
            "id": "JO.AZ"
        },
        {
            "id": "JO.BA"
        },
        {
            "id": "JO.IR"
        },
        {
            "id": "JO.JA"
        },
        {
            "id": "JO.KA"
        },
        {
            "id": "JO.MN"
        },
        {
            "id": "JO.MD"
        }
    ],
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
                "id": "Am",
                "shapeid": "myCustomShape",
                "x": "129.49",
                "y": "206.41",
                "label": "Amman",
                "labelpos": "right"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "124.39",
                "y": "115.67",
                "label": "Irbid"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "141.72",
                "y": "183.98",
                "label": "Az Zarqa",
                "labelpos": "right"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "126.43",
                "y": "327.75",
                "label": "Al Karak",
                "labelpos": "right"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape",
                "x": "145.8",
                "y": "403.2",
                "label": "Ma'an"
            },
            {
                "id": "06",
                "shapeid": "newCustomShape",
                "x": "26.5",
                "y": "527.59",
                "label": "Al Aqabah",
                "labelpos": "right"
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
        "showlabels": "0",
        "showmarkerlabels": "1",
        "fillcolor": "F1f1f1",
        "bordercolor": "999999",
        "basefont": "Verdana",
        "basefontsize": "10",
        "markerbordercolor": "000000",
        "markerbgcolor": "FF5904",
        "markerradius": "6",
        "legendposition": "bottom",
        "usehovercolor": "1",
        "showmarkertooltip": "1"
    },
    "data": [
        {
            "id": "JO.AJ"
        },
        {
            "id": "JO.AM"
        },
        {
            "id": "JO.AQ"
        },
        {
            "id": "JO.MA"
        },
        {
            "id": "JO.AT"
        },
        {
            "id": "JO.AZ"
        },
        {
            "id": "JO.BA"
        },
        {
            "id": "JO.IR"
        },
        {
            "id": "JO.JA"
        },
        {
            "id": "JO.KA"
        },
        {
            "id": "JO.MN"
        },
        {
            "id": "JO.MD"
        }
    ],
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
                "id": "Am",
                "x": "129.49",
                "y": "206.41",
                "label": "Amman",
                "labelpos": "right"
            },
            {
                "id": "01",
                "x": "124.39",
                "y": "115.67",
                "label": "Irbid"
            },
            {
                "id": "02",
                "x": "141.72",
                "y": "183.98",
                "label": "Az Zarqa",
                "labelpos": "right"
            },
            {
                "id": "03",
                "x": "126.43",
                "y": "327.75",
                "label": "Al Karak",
                "labelpos": "right"
            },
            {
                "id": "05",
                "x": "145.8",
                "y": "403.2",
                "label": "Ma'an"
            },
            {
                "id": "06",
                "x": "26.5",
                "y": "527.59",
                "label": "Al Aqabah",
                "labelpos": "right"
            }
        ],
        "application": [
            {
                "id": "Am",
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
                "id": "05",
                "shapeid": "newCustomShape"
            },
            {
                "id": "06",
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
