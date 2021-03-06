---
# Front matter (even empty) required for Jekyll to process
---

#### Map Name: Scotland

#### JavaScript Alias: maps/scotland


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
                "id": "ED",
                "shapeid": "myCustomShape",
                "x": "369.63",
                "y": "371.62",
                "label": "Edinburgh",
                "labelpos": "bottom"
            },
            {
                "id": "01",
                "shapeid": "newCustomShape",
                "x": "265.58",
                "y": "166.48",
                "label": "Inverness",
                "labelpos": "left"
            },
            {
                "id": "02",
                "shapeid": "newCustomShape",
                "x": "454.86",
                "y": "161.53",
                "label": "Peterhead",
                "labelpos": "left"
            },
            {
                "id": "03",
                "shapeid": "newCustomShape",
                "x": "437.02",
                "y": "195.22",
                "label": "Aberdeen",
                "labelpos": "left"
            },
            {
                "id": "04",
                "shapeid": "newCustomShape",
                "x": "365.67",
                "y": "302.25",
                "label": "Dundee",
                "labelpos": "left"
            },
            {
                "id": "05",
                "shapeid": "newCustomShape",
                "x": "343.87",
                "y": "312.16",
                "label": "Perth",
                "labelpos": "left"
            },
            {
                "id": "06",
                "shapeid": "newCustomShape",
                "x": "256.66",
                "y": "436.03",
                "label": "Ayr",
                "labelpos": "right"
            },
            {
                "id": "07",
                "shapeid": "newCustomShape",
                "x": "269.54",
                "y": "377.56",
                "label": "Glasgow",
                "labelpos": "right"
            },
            {
                "id": "08",
                "shapeid": "newCustomShape",
                "x": "346.84",
                "y": "485.58",
                "label": "Dumfries",
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
                "id": "ED",
                "x": "369.63",
                "y": "371.62",
                "label": "Edinburgh",
                "labelpos": "bottom"
            },
            {
                "id": "01",
                "x": "265.58",
                "y": "166.48",
                "label": "Inverness",
                "labelpos": "left"
            },
            {
                "id": "02",
                "x": "454.86",
                "y": "161.53",
                "label": "Peterhead",
                "labelpos": "left"
            },
            {
                "id": "03",
                "x": "437.02",
                "y": "195.22",
                "label": "Aberdeen",
                "labelpos": "left"
            },
            {
                "id": "04",
                "x": "365.67",
                "y": "302.25",
                "label": "Dundee",
                "labelpos": "left"
            },
            {
                "id": "05",
                "x": "343.87",
                "y": "312.16",
                "label": "Perth",
                "labelpos": "left"
            },
            {
                "id": "06",
                "x": "256.66",
                "y": "436.03",
                "label": "Ayr",
                "labelpos": "right"
            },
            {
                "id": "07",
                "x": "269.54",
                "y": "377.56",
                "label": "Glasgow",
                "labelpos": "right"
            },
            {
                "id": "08",
                "x": "346.84",
                "y": "485.58",
                "label": "Dumfries",
                "labelpos": "left"
            }
        ],
        "application": [
            {
                "id": "ED",
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
