---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: Burma

#### JavaScript Alias: maps/burma


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
            "id": "MM.AY"
        },
        {
            "id": "MM.BA"
        },
        {
            "id": "MM.CH"
        },
        {
            "id": "MM.KC"
        },
        {
            "id": "MM.KH"
        },
        {
            "id": "MM.KN"
        },
        {
            "id": "MM.MG"
        },
        {
            "id": "MM.MD"
        },
        {
            "id": "MM.MO"
        },
        {
            "id": "MM.RA"
        },
        {
            "id": "MM.SA"
        },
        {
            "id": "MM.SH"
        },
        {
            "id": "MM.TN"
        },
        {
            "id": "MM.YA"
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
                "id": "YA",
                "shapeid": "myCustomShape",
                "x": "259.39",
                "y": "734.39",
                "label": "Yangon"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "356.03",
                "y": "170.84",
                "label": "Myitkina",
                "labelpos": "right"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "341.79",
                "y": "266.46",
                "label": "Bhamo"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "213.62",
                "y": "380.39",
                "label": "Monywa"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape",
                "x": "191.24",
                "y": "470.93",
                "label": "Chauk",
                "labelpos": "left"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape",
                "x": "61.03",
                "y": "527.89",
                "label": "Sittwe",
                "labelpos": "left"
            },
            {
                "id": "06",
                "shapeid": "newCustomShape",
                "x": "216.67",
                "y": "586.89",
                "label": "Pyay"
            },
            {
                "id": "07",
                "shapeid": "newCustomShape",
                "x": "283.81",
                "y": "699.81",
                "label": "Bago"
            },
            {
                "id": "08",
                "shapeid": "newCustomShape",
                "x": "170.89",
                "y": "746.6",
                "label": "Pathein"
            },
            {
                "id": "09",
                "shapeid": "newCustomShape",
                "x": "345.86",
                "y": "759.82",
                "label": "Mawlamyine",
                "labelpos": "right"
            },
            {
                "id": "10",
                "shapeid": "newCustomShape",
                "x": "394.68",
                "y": "905.29",
                "label": "Dawei"
            },
            {
                "id": "11",
                "shapeid": "newCustomShape",
                "x": "430.29",
                "y": "1018.2",
                "label": "Beik",
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
        "legendposition": "bottom",
        "usehovercolor": "1",
        "showmarkertooltip": "1"
    },
    "data": [
        {
            "id": "MM.AY"
        },
        {
            "id": "MM.BA"
        },
        {
            "id": "MM.CH"
        },
        {
            "id": "MM.KC"
        },
        {
            "id": "MM.KH"
        },
        {
            "id": "MM.KN"
        },
        {
            "id": "MM.MG"
        },
        {
            "id": "MM.MD"
        },
        {
            "id": "MM.MO"
        },
        {
            "id": "MM.RA"
        },
        {
            "id": "MM.SA"
        },
        {
            "id": "MM.SH"
        },
        {
            "id": "MM.TN"
        },
        {
            "id": "MM.YA"
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
                "id": "YA",
                "x": "259.39",
                "y": "734.39",
                "label": "Yangon"
            },
            {
                "id": "01",
                "x": "356.03",
                "y": "170.84",
                "label": "Myitkina",
                "labelpos": "right"
            },
            {
                "id": "02",
                "x": "341.79",
                "y": "266.46",
                "label": "Bhamo"
            },
            {
                "id": "03",
                "x": "213.62",
                "y": "380.39",
                "label": "Monywa"
            },
            {
                "id": "04",
                "x": "191.24",
                "y": "470.93",
                "label": "Chauk",
                "labelpos": "left"
            },
            {
                "id": "05",
                "x": "61.03",
                "y": "527.89",
                "label": "Sittwe",
                "labelpos": "left"
            },
            {
                "id": "06",
                "x": "216.67",
                "y": "586.89",
                "label": "Pyay"
            },
            {
                "id": "07",
                "x": "283.81",
                "y": "699.81",
                "label": "Bago"
            },
            {
                "id": "08",
                "x": "170.89",
                "y": "746.6",
                "label": "Pathein"
            },
            {
                "id": "09",
                "x": "345.86",
                "y": "759.82",
                "label": "Mawlamyine",
                "labelpos": "right"
            },
            {
                "id": "10",
                "x": "394.68",
                "y": "905.29",
                "label": "Dawei"
            },
            {
                "id": "11",
                "x": "430.29",
                "y": "1018.2",
                "label": "Beik",
                "labelpos": "right"
            }
        ],
        "application": [
            {
                "id": "YA",
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
            },
            {
                "id": "09",
                "shapeid": "newCustomShape"
            },
            {
                "id": "10",
                "shapeid": "newCustomShape"
            },
            {
                "id": "11",
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
