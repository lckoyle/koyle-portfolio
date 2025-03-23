# Custom Map Style for Colorado Coalition for the Homeless

## Map Style Color Palette

| **Feature Type**        | **Element Type**   | **Stylers**                                         |
|-------------------------|--------------------|-----------------------------------------------------|
| **All**                 | Geometry           | Color: #d0d8df                                      |
| **All**                 | Text Fill          | Color: #353c65                                      |
| **All**                 | Text Outline       | Color: #ffd27c, Lightness: 80                      |
| **Administrative**      | Stroke             | Color: #20647c                                      |
| **Land Parcel**         | Stroke             | Color: #20647c                                      |
| **Land Parcel**         | Labels             | Color: #20647c                                      |
| **Land Parcel**         | Text Fill          | Color: #20647c                                      |
| **Natural**             | Geometry           | Color: #20647c, Lightness: 20                      |
| **Points of Interest**  | Geometry           | Color: #ffd27c, Lightness: 30                      |
| **Points of Interest**  | Text Fill          | Color: #20647c                                      |
| **Park**                | Fill               | Color: #3b8870                                      |
| **Park**                | Text Fill          | Color: #20647c                                      |
| **Road**                | Geometry           | Color: #f5f1e6                                      |
| **Highway**             | Geometry           | Color: #52aab3                                      |
| **Highway**             | Stroke             | Color: #353c65                                      |
| **Arterial**            | Geometry           | Color: #353c65                                      |
| **Local**               | Geometry           | Color: #52aab3                                      |
| **Local**               | Labels             | Color: #20647c                                      |
| **Line**                | Geometry           | Color: #52aab3                                      |
| **Line**                | Text Fill          | Color: #52aab3                                      |
| **Line**                | Text Outline       | Color: #20647c                                      |
| **Station**             | Text Fill          | Color: #20647c                                      |
| **Water**               | Fill               | Color: #52aab3                                      |
| **Water**               | Text Fill          | Color: #20647c                                      |



## Design Decisions

## Testing
The map was tested at multiple zoom levels to ensure usability. The chosen style provides clarity in city maps while being visually appealing.

![Screenshot 2025-03-23 at 5 18 07 PM](https://github.com/user-attachments/assets/af4dea8e-3fac-4e5b-b6a1-059bbbc10dea)
![Screenshot 2025-03-23 at 5 18 37 PM](https://github.com/user-attachments/assets/43957fad-987e-4431-b692-4035a6214e31)
![Screenshot 2025-03-23 at 5 19 48 PM](https://github.com/user-attachments/assets/96519b63-e2e9-4b30-8c85-bb6742b452d2)
![Screenshot 2025-03-23 at 5 19 14 PM](https://github.com/user-attachments/assets/685c1ec7-eece-480e-8fda-2c4b43456f97)


## JSON Code

[
  {
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#d0d8df"
      }
    ]
  },
  {
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#353c65"
      },
      {
        "saturation": 40
      }
    ]
  },
  {
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#ffd27c"
      },
      {
        "lightness": 80
      }
    ]
  },
  {
    "featureType": "administrative",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#20647c"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#20647c"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "labels",
    "stylers": [
      {
        "color": "#20647c"
      },
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "administrative.land_parcel",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#20647c"
      }
    ]
  },
  {
    "featureType": "landscape.natural",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#20647c"
      },
      {
        "lightness": 20
      }
    ]
  },
  {
    "featureType": "poi",
    "stylers": [
      {
        "lightness": 55
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#ffd27c"
      },
      {
        "lightness": 30
      },
      {
        "visibility": "on"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "poi",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#20637c"
      }
    ]
  },
  {
    "featureType": "poi.attraction",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "poi.business",
    "elementType": "geometry",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "poi.government",
    "stylers": [
      {
        "visibility": "on"
      }
    ]
  },
  {
    "featureType": "poi.government",
    "elementType": "geometry",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#3b8870"
      }
    ]
  },
  {
    "featureType": "poi.park",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#20647c"
      }
    ]
  },
  {
    "featureType": "poi.school",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "poi.sports_complex",
    "stylers": [
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "road",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#f5f1e6"
      }
    ]
  },
  {
    "featureType": "road.arterial",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#52aab3"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#52aab3"
      }
    ]
  },
  {
    "featureType": "road.highway",
    "elementType": "geometry.stroke",
    "stylers": [
      {
        "color": "#353c65"
      }
    ]
  },
  {
    "featureType": "road.local",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#52aab3"
      }
    ]
  },
  {
    "featureType": "road.local",
    "elementType": "labels",
    "stylers": [
      {
        "color": "#20647c"
      },
      {
        "visibility": "off"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "geometry",
    "stylers": [
      {
        "color": "#52aab2"
      },
      {
        "lightness": 20
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#52aab3"
      }
    ]
  },
  {
    "featureType": "transit.line",
    "elementType": "labels.text.stroke",
    "stylers": [
      {
        "color": "#20647c"
      }
    ]
  },
  {
    "featureType": "transit.station",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#20647c"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "geometry.fill",
    "stylers": [
      {
        "color": "#52aab3"
      }
    ]
  },
  {
    "featureType": "water",
    "elementType": "labels.text.fill",
    "stylers": [
      {
        "color": "#20647c"
      }
    ]
  }
]
