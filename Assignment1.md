# Custom Map Style for Colorado Coalition for the Homeless

## Bid Introduction

This proposal outlines the deliverables and approach for Phase 1 of the map redesign and integration project for Colorado Coalition for the Homeless. The goal of this phase is to create a custom map that aligns with the organization’s existing design and meets functional requirements.

## Map Style Color Palette

| Color Name     | Hex Code   | Swatch |
|----------------|------------|--------|
| Light Gray     | #d0d8df    | <img width="152" alt="Screenshot 2025-03-23 at 5 56 08 PM" src="https://github.com/user-attachments/assets/5ea0cfd9-0396-4770-b9f4-571ae5d20b7f" />|
| Dark Blue      | #353c65    | <img width="150" alt="Screenshot 2025-03-23 at 5 55 34 PM" src="https://github.com/user-attachments/assets/184a83c8-8def-4e4e-8ebe-8d4f764f8338" />|
| Light Yellow   | #ffd27c (Lightness 80) | <img width="151" alt="Screenshot 2025-03-23 at 5 54 27 PM" src="https://github.com/user-attachments/assets/d4c3ec13-bc3c-45fd-8181-f43af0e55020" />|
| Teal           | #20647c    |  <img width="150" alt="Screenshot 2025-03-23 at 5 53 21 PM" src="https://github.com/user-attachments/assets/e03d15c2-5230-4878-af0b-0afc951512dd" />|
| Green          | #3b8870    | <img width="149" alt="Screenshot 2025-03-23 at 6 00 12 PM" src="https://github.com/user-attachments/assets/6b08a067-c413-4783-8b90-d75662aaa877" /> |
| Off-White      | #f5f1e6    | <img width="151" alt="Screenshot 2025-03-23 at 5 57 27 PM" src="https://github.com/user-attachments/assets/eccbec1b-dbf0-44e3-b6b9-61e66a681654" /> |
| Turqouise      | #52aab3    | <img width="148" alt="Screenshot 2025-03-23 at 5 58 14 PM" src="https://github.com/user-attachments/assets/9b866d48-c6c6-44ad-9ea9-f9fcc37ea74e" />|


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

I created a map for the Colorado Coalition for the Homeless to provide stakeholders with clear, accessible information about emergency shelters, affordable housing, and social services in the Denver metro area. In developing the map, I carefully considered the coalition's existing branding materials, such as the logo, reports, and website. This enabled me to establish a color palette that was both clean and cohesive, while remaining brand-appropriate to ensure the map aligns with the Coalition's visual identity.

A primary goal was to ensure that all features were legible at all zoom levels. Strong contrast between roads, parks, and natural elements ensures that each feature is visually clear and stands out against the neutral background. I also avoided using overly bright or saturated colors to keep the design balanced and easy on the eyes.

- #52aab3 and #ffd27c: Turqouise and yellow were used for road features and points of interest to draw attention without overwhelming the map, ensuring important areas stand out.

- #3b8870: I shifted from the given color palette to include a green shade, which was used for park areas. This was to provide contrast and help users orient themselves within the city, while still maintaining a visually balanced design.

- #d0d8df and #f5f1e6: for the background and road geometries provide softness to the map and a foundation allowing for contrast.

- #353c65 for text fill ensure that labels are readable against the lighter background.

## Testing
Before finalizing the design, I tested the map at various zoom extents to ensure usability at both large and small scales. This included checking that road names, points of interest, and other labels remained legible at different zoom levels.

![Screenshot 2025-03-23 at 5 18 07 PM](https://github.com/user-attachments/assets/af4dea8e-3fac-4e5b-b6a1-059bbbc10dea)
![Screenshot 2025-03-23 at 5 18 37 PM](https://github.com/user-attachments/assets/43957fad-987e-4431-b692-4035a6214e31)
![Screenshot 2025-03-23 at 5 19 48 PM](https://github.com/user-attachments/assets/96519b63-e2e9-4b30-8c85-bb6742b452d2)
![Screenshot 2025-03-23 at 5 19 14 PM](https://github.com/user-attachments/assets/685c1ec7-eece-480e-8fda-2c4b43456f97)


## JSON Code

<a href="https://raw.githubusercontent.com/lckoyle/koyle-portfolio/main/mapJSON.json" download>Click here to access the JSON style file </a>

Download here: [mapJSON.json](https://github.com/user-attachments/files/19411759/mapJSON.json)
