# Blackland House Build Record

**Open as a standalone page:** https://borngifted.github.io/blackland-build-record/

**Work Official LLC · Leo Marshall residence · 201 Blackland Dr NW, Atlanta** · Prepared 17 September 2026 · cabinetry verified 1:1 against the DDS DWG

The visuals for this house were not typed into a chatbot. A full 3D replica of the home was built in Blender from the DDS cabinetry drawings, the Doden Casa concept deck and the Canva lighting selections. Every image on this page was rendered from that model, and each one is shown next to the Blender screenshot it came from.

3D model in Blender 4.4 · three storeys · 21 rooms of cabinetry · 33 concept views rebuilt · 26 presentation views

| The 3D house with its roof lifted off | The same model inside Blender |
|---|---|
| <img src="img/proof_dollhouse_eevee.jpg" alt="Dollhouse render" width="480"> | <img src="img/proof_ui_openroof_outliner.jpg" alt="Blender interface" width="480"> |

## Three source documents

| DDS cabinetry drawings | Doden Casa concept deck | Canva “Blackland Lighting Selections” |
|---|---|---|
| <img src="img/dds_01.jpg" alt="DDS sheet 1" width="300"> | <img src="img/slide_s03.jpg" alt="Concept slide 3" width="300"> | <img src="img/canva_canva_e83754ce-e275-4a46-b933-31e5cf57b60e.jpg" alt="Canva board" width="300"> |
| `杜登莎—美国LEO 2026.9.14.dwg` · 38 sheets. Plans and elevations for 21 rooms, dimensioned in millimetres. Every cabinet, counter, niche and vanity in the model is sized from these sheets. | `USA -LEO 2026-08-30.pdf` · 36 slides. The per-room concept renders. They set the finishes (oak, walnut, calacatta, breccia, travertine, brass) and the camera angles rebuilt below. | canva.link/8awymtdbhe0exyx · 21 RH products. The lighting, mirror and fixture selections referenced for the pendants, sconces and mirrors. |

<p><img src="img/canva_RH_prod21280349.jpg" alt="prod21280349" width="90"> <img src="img/canva_RH_prod24980147.jpg" alt="prod24980147" width="90"> <img src="img/canva_RH_prod37340020.jpg" alt="prod37340020" width="90"> <img src="img/canva_RH_prod38810175.jpg" alt="prod38810175" width="90"> <img src="img/canva_RH_prod38810179.jpg" alt="prod38810179" width="90"> <img src="img/canva_RH_prod39390174.jpg" alt="prod39390174" width="90"> <img src="img/canva_RH_prod28840074.jpg" alt="prod28840074" width="90"> <img src="img/canva_RH_prod18950600.jpg" alt="prod18950600" width="90"> <img src="img/canva_RH_prod20520249.jpg" alt="prod20520249" width="90"> <img src="img/canva_RH_prod14880045.jpg" alt="prod14880045" width="90"> <img src="img/canva_RH_prod39390168.jpg" alt="prod39390168" width="90"> <img src="img/canva_RH_prod24980162.jpg" alt="prod24980162" width="90"> <img src="img/canva_RH_prod39390157.jpg" alt="prod39390157" width="90"> <img src="img/canva_RH_prod25180974.jpg" alt="prod25180974" width="90"> <img src="img/canva_RH_prod38810177.jpg" alt="prod38810177" width="90"> <img src="img/canva_RH_prod18950577.jpg" alt="prod18950577" width="90"> <img src="img/canva_RH_prod24700324.jpg" alt="prod24700324" width="90"> <img src="img/canva_RH_prod38810491.jpg" alt="prod38810491" width="90"> <img src="img/canva_RH_prod31700055.jpg" alt="prod31700055" width="90"> <img src="img/canva_RH_prod18950256.jpg" alt="prod18950256" width="90"> <img src="img/canva_RH_prod38810231.jpg" alt="prod38810231" width="90"></p>

## How each image was made

| 1 · Read the drawings | 2 · Build the house in 3D | 3 · Match the concept views | 4 · Render from the model | 5 · Photoreal pass |
|---|---|---|---|---|
| <img src="img/dds_01.jpg" alt="DDS" width="200"> | <img src="img/proof_ui_cabinet_dimensions.jpg" alt="Cabinet in Blender" width="200"> | <img src="img/ui_s03.jpg" alt="Camera match" width="200"> | <img src="img/render_s03.jpg" alt="Blender render" width="200"> | <img src="img/hf_05_kitchen_hood_wall.jpg" alt="Higgsfield" width="200"> |
| Each DDS sheet is read room by room: cabinet widths, depths and heights in millimetres, plus windows and doors. | The house is modelled in Blender at real scale. Here a kitchen base cabinet is selected and Blender reports 1064 mm, the figure on DDS sheet 3. | For each of the 33 concept slides a camera is placed in the model in the same room, facing the same wall. | Blender renders the view directly. Nothing is invented: what you see is the geometry and materials of the model. | For presentation, the Blender render is refined with Higgsfield (cloud) or ComfyUI (local). Both start from the render and keep its layout and camera. |

## The 3D build in Blender

| Kitchen wall B base cabinet 1 selected: 1064 mm wide, 580 deep, 760 high, matching the DDS sheet | Wireframe of the whole model |
|---|---|
| <img src="img/proof_ui_cabinet_dimensions.jpg" alt="Cabinet dimensions" width="480"> | <img src="img/proof_aerial_wireframe.jpg" alt="Wireframe" width="480"> |

| Main level from above | Upper level | Basement |
|---|---|---|
| <img src="img/proof_plan_main.jpg" alt="Main plan" width="320"> | <img src="img/proof_plan_upper.jpg" alt="Upper plan" width="320"> | <img src="img/proof_plan_basement.jpg" alt="Basement plan" width="320"> |

## Measured 1:1 against the DDS drawing

On 17 September 2026 every room was re-read from the DDS CAD file itself (true scale, 1 unit = 1 mm) and the model was rebuilt from those numbers. A script then measures the finished Blender model against the drawing: **295 of 295 cabinetry parts are within 0.5 mm** in position, width, depth, height and elevation. Millimetres, drawing → model.

| Room | Cabinet wall, face to face | Room depth | Ceiling | Parts checked | Largest deviation |
|---|---|---|---|---|---|
| 1st Floor Kitchen | 6436 → 6436 | 5344 → 5344 | 3000 → 3000 | 38 | 0.0 |
| 1st Floor Pantry | 4234 → 4234 | 2620 → 2620 | 2800 → 2800 | 14 | 0.0 |
| 1st Floor Office | 5009 → 5009 | 1687 (plan cropped in DWG) | 3000 → 3000 | 13 | 0.0 |
| 1st Floor Aisle | 5009 → 5009 | 1000 (plan cropped in DWG) | 3000 → 3000 | 11 | 0.0 |
| 1st Floor Laundry | 4657 → 4657 | 1560 → 1560 | 2800 → 2800 | 20 | 0.0 |
| 1st Floor Mud | 1748 → 1748 | 833 (plan cropped in DWG) | 2600 → 2600 | 11 | 0.0 |
| 1st Floor Powder-1 | 1787 → 1787 | 1564 → 1564 | 2800 → 2800 | 9 | 0.0 |
| 1st Floor Primary En Suite | 5703 → 5703 | 1215 (plan cropped in DWG) | 3000 → 3000 | 16 | 0.0 |
| 1st Floor Powder-2 | 1709 → 1709 | 1536 → 1536 | 2800 → 2800 | 4 | 0.0 |
| 1st Floor Butler's Pantry | 3263 → 3263 | 826 → 826 | 2800 → 2800 | 12 | 0.0 |
| 2nd Floor Laundry | 3961 → 3961 | 3483 → 3483 | 2800 → 2800 | 30 | 0.0 |
| 2nd Floor Powder | 1857 → 1857 | 1549 → 1549 | 2800 → 2800 | 4 | 0.0 |
| 2nd Floor En Suite | 2448 → 2448 | 1000 (plan cropped in DWG) | 2800 → 2800 | 18 | 0.0 |
| 2nd Floor Bath 3 | 2827 → 2827 | 1581 → 1581 | 2800 → 2800 | 9 | 0.0 |
| 2nd Floor Bath 4 | 2686 → 2686 | 1842 → 1842 | 2800 → 2800 | 9 | 0.0 |
| 2nd Floor Bath 5 | 3552 → 3552 | 1917 → 1917 | 2800 → 2800 | 11 | 0.0 |
| 2nd Floor Bath 6 | 3550 → 3550 | 1869 → 1869 | 2800 → 2800 | 11 | 0.0 |
| 3rd Floor Bath 7 | 2214 → 2214 | 745 (plan cropped in DWG) | 2800 → 2800 | 8 | 0.0 |
| 3rd Floor Bath 8 | 2146 → 2146 | 1000 (plan cropped in DWG) | 2800 → 2800 | 10 | 0.0 |
| 3rd Floor Bar | 2913 → 2913 | 1000 (plan cropped in DWG) | 2800 → 2800 | 8 | 0.0 |
| 3rd Floor Bar/Kitchenette | 5000 → 5000 | 3097 (plan cropped in DWG) | 2800 → 2800 | 29 | 0.0 |

## Concept views rebuilt in 3D, room by room

Each row shows a slide from the Doden Casa deck, the Blender interface with the model at the matching camera, and the render that came out of Blender. Click any image to open it full size.

### Kitchen · 1st floor

DDS cabinetry drawing this room was built from (sheet 1, mm):

<img src="img/dds_01.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s03.jpg" alt="slide 03" width="320"> | <img src="img/ui_s03.jpg" alt="Blender" width="320"> | <img src="img/render_s03.jpg" alt="render" width="320"> |
| <img src="img/ref_s04.jpg" alt="slide 04" width="320"> | <img src="img/ui_s04.jpg" alt="Blender" width="320"> | <img src="img/render_s04.jpg" alt="render" width="320"> |
| <img src="img/ref_s05.jpg" alt="slide 05" width="320"> | <img src="img/ui_s05.jpg" alt="Blender" width="320"> | <img src="img/render_s05.jpg" alt="render" width="320"> |
| <img src="img/ref_s06.jpg" alt="slide 06" width="320"> | <img src="img/ui_s06.jpg" alt="Blender" width="320"> | <img src="img/render_s06.jpg" alt="render" width="320"> |
| <img src="img/ref_s07.jpg" alt="slide 07" width="320"> | <img src="img/ui_s07.jpg" alt="Blender" width="320"> | <img src="img/render_s07.jpg" alt="render" width="320"> |
| <img src="img/ref_s08.jpg" alt="slide 08" width="320"> | <img src="img/ui_s08.jpg" alt="Blender" width="320"> | <img src="img/render_s08.jpg" alt="render" width="320"> |

### Pantry · 1st floor

DDS cabinetry drawing this room was built from (sheet 9, mm):

<img src="img/dds_09.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s09.jpg" alt="slide 09" width="320"> | <img src="img/ui_s09.jpg" alt="Blender" width="320"> | <img src="img/render_s09.jpg" alt="render" width="320"> |
| <img src="img/ref_s10.jpg" alt="slide 10" width="320"> | <img src="img/ui_s10.jpg" alt="Blender" width="320"> | <img src="img/render_s10.jpg" alt="render" width="320"> |

### Office library · 1st floor

DDS cabinetry drawing this room was built from (sheet 12, mm):

<img src="img/dds_12.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s11.jpg" alt="slide 11" width="320"> | <img src="img/ui_s11.jpg" alt="Blender" width="320"> | <img src="img/render_s11.jpg" alt="render" width="320"> |
| <img src="img/ref_s12.jpg" alt="slide 12" width="320"> | <img src="img/ui_s12.jpg" alt="Blender" width="320"> | <img src="img/render_s12.jpg" alt="render" width="320"> |

### Laundry · 1st floor

DDS cabinetry drawing this room was built from (sheet 14, mm):

<img src="img/dds_14.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s13.jpg" alt="slide 13" width="320"> | <img src="img/ui_s13.jpg" alt="Blender" width="320"> | <img src="img/render_s13.jpg" alt="render" width="320"> |

### Mud room · 1st floor

DDS cabinetry drawing this room was built from (sheet 17, mm):

<img src="img/dds_17.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s14.jpg" alt="slide 14" width="320"> | <img src="img/ui_s14.jpg" alt="Blender" width="320"> | <img src="img/render_s14.jpg" alt="render" width="320"> |

### Powder 1 · 1st floor

DDS cabinetry drawing this room was built from (sheet 18, mm):

<img src="img/dds_18.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s15.jpg" alt="slide 15" width="320"> | <img src="img/ui_s15.jpg" alt="Blender" width="320"> | <img src="img/render_s15.jpg" alt="render" width="320"> |

### Primary en suite · 1st floor

DDS cabinetry drawing this room was built from (sheet 19, mm):

<img src="img/dds_19.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s16.jpg" alt="slide 16" width="320"> | <img src="img/ui_s16.jpg" alt="Blender" width="320"> | <img src="img/render_s16.jpg" alt="render" width="320"> |
| <img src="img/ref_s17.jpg" alt="slide 17" width="320"> | <img src="img/ui_s17.jpg" alt="Blender" width="320"> | <img src="img/render_s17.jpg" alt="render" width="320"> |

### Powder 2 · 1st floor

DDS cabinetry drawing this room was built from (sheet 21, mm):

<img src="img/dds_21.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s18.jpg" alt="slide 18" width="320"> | <img src="img/ui_s18.jpg" alt="Blender" width="320"> | <img src="img/render_s18.jpg" alt="render" width="320"> |

### Butler's pantry · 1st floor

DDS cabinetry drawing this room was built from (sheet 22, mm):

<img src="img/dds_22.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s19.jpg" alt="slide 19" width="320"> | <img src="img/ui_s19.jpg" alt="Blender" width="320"> | <img src="img/render_s19.jpg" alt="render" width="320"> |

### Laundry · 2nd floor

DDS cabinetry drawing this room was built from (sheet 23, mm):

<img src="img/dds_23.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s20.jpg" alt="slide 20" width="320"> | <img src="img/ui_s20.jpg" alt="Blender" width="320"> | <img src="img/render_s20.jpg" alt="render" width="320"> |
| <img src="img/ref_s21.jpg" alt="slide 21" width="320"> | <img src="img/ui_s21.jpg" alt="Blender" width="320"> | <img src="img/render_s21.jpg" alt="render" width="320"> |
| <img src="img/ref_s22.jpg" alt="slide 22" width="320"> | <img src="img/ui_s22.jpg" alt="Blender" width="320"> | <img src="img/render_s22.jpg" alt="render" width="320"> |
| <img src="img/ref_s23.jpg" alt="slide 23" width="320"> | <img src="img/ui_s23.jpg" alt="Blender" width="320"> | <img src="img/render_s23.jpg" alt="render" width="320"> |

### Powder · 2nd floor

DDS cabinetry drawing this room was built from (sheet 27, mm):

<img src="img/dds_27.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s24.jpg" alt="slide 24" width="320"> | <img src="img/ui_s24.jpg" alt="Blender" width="320"> | <img src="img/render_s24.jpg" alt="render" width="320"> |

### En suite · 2nd floor

DDS cabinetry drawing this room was built from (sheet 28, mm):

<img src="img/dds_28.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s25.jpg" alt="slide 25" width="320"> | <img src="img/ui_s25.jpg" alt="Blender" width="320"> | <img src="img/render_s25.jpg" alt="render" width="320"> |

### Bath 3 · 2nd floor

DDS cabinetry drawing this room was built from (sheet 29, mm):

<img src="img/dds_29.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s26.jpg" alt="slide 26" width="320"> | <img src="img/ui_s26.jpg" alt="Blender" width="320"> | <img src="img/render_s26.jpg" alt="render" width="320"> |

### Bath 4 · 2nd floor

DDS cabinetry drawing this room was built from (sheet 30, mm):

<img src="img/dds_30.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s27.jpg" alt="slide 27" width="320"> | <img src="img/ui_s27.jpg" alt="Blender" width="320"> | <img src="img/render_s27.jpg" alt="render" width="320"> |

### Bath 5 · 2nd floor

DDS cabinetry drawing this room was built from (sheet 31, mm):

<img src="img/dds_31.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s28.jpg" alt="slide 28" width="320"> | <img src="img/ui_s28.jpg" alt="Blender" width="320"> | <img src="img/render_s28.jpg" alt="render" width="320"> |

### Bath 6 · 2nd floor

DDS cabinetry drawing this room was built from (sheet 32, mm):

<img src="img/dds_32.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s29.jpg" alt="slide 29" width="320"> | <img src="img/ui_s29.jpg" alt="Blender" width="320"> | <img src="img/render_s29.jpg" alt="render" width="320"> |

### Bath 7 · Basement

DDS cabinetry drawing this room was built from (sheet 33, mm):

<img src="img/dds_33.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s30.jpg" alt="slide 30" width="320"> | <img src="img/ui_s30.jpg" alt="Blender" width="320"> | <img src="img/render_s30.jpg" alt="render" width="320"> |

### Bath 8 · Basement

DDS cabinetry drawing this room was built from (sheet 34, mm):

<img src="img/dds_34.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s31.jpg" alt="slide 31" width="320"> | <img src="img/ui_s31.jpg" alt="Blender" width="320"> | <img src="img/render_s31.jpg" alt="render" width="320"> |

### Bar niche · Basement

DDS cabinetry drawing this room was built from (sheet 35, mm):

<img src="img/dds_35.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s32.jpg" alt="slide 32" width="320"> | <img src="img/ui_s32.jpg" alt="Blender" width="320"> | <img src="img/render_s32.jpg" alt="render" width="320"> |

### Bar and kitchenette · Basement

DDS cabinetry drawing this room was built from (sheet 36, mm):

<img src="img/dds_36.jpg" alt="DDS sheet" width="520">

| Concept slide · Doden Casa deck | Blender · the 3D model at the same camera | Blender render · straight from the model |
|---|---|---|
| <img src="img/ref_s33.jpg" alt="slide 33" width="320"> | <img src="img/ui_s33.jpg" alt="Blender" width="320"> | <img src="img/render_s33.jpg" alt="render" width="320"> |
| <img src="img/ref_s34.jpg" alt="slide 34" width="320"> | <img src="img/ui_s34.jpg" alt="Blender" width="320"> | <img src="img/render_s34.jpg" alt="render" width="320"> |
| <img src="img/ref_s35.jpg" alt="slide 35" width="320"> | <img src="img/ui_s35.jpg" alt="Blender" width="320"> | <img src="img/render_s35.jpg" alt="render" width="320"> |

## System in play: Higgsfield

The 26 presentation views. Left to right: the model in Blender, the Blender render, and the Higgsfield photoreal pass that starts from that render. The layout, cabinetry and camera are the model’s; Higgsfield adds photographic light and texture.

| View | Blender · 3D model | Blender render | Higgsfield photoreal pass |
|---|---|---|---|
| Exterior front | <img src="img/vui_01_exterior_front.jpg" alt="Blender" width="260"> | <img src="img/blend_01_exterior_front.jpg" alt="render" width="260"> | <img src="img/hf_01_exterior_front.jpg" alt="Higgsfield" width="260"> |
| Exterior rear pool | <img src="img/vui_02_exterior_rear_pool.jpg" alt="Blender" width="260"> | <img src="img/blend_02_exterior_rear_pool.jpg" alt="render" width="260"> | <img src="img/hf_02_exterior_rear_pool.jpg" alt="Higgsfield" width="260"> |
| Aerial | <img src="img/vui_03_aerial.jpg" alt="Blender" width="260"> | <img src="img/blend_03_aerial.jpg" alt="render" width="260"> | <img src="img/hf_03_aerial.jpg" alt="Higgsfield" width="260"> |
| Exterior front straight | <img src="img/vui_04_exterior_front_straight.jpg" alt="Blender" width="260"> | <img src="img/blend_04_exterior_front_straight.jpg" alt="render" width="260"> | <img src="img/hf_04_exterior_front_straight.jpg" alt="Higgsfield" width="260"> |
| Kitchen hood wall | <img src="img/vui_05_kitchen_hood_wall.jpg" alt="Blender" width="260"> | <img src="img/blend_05_kitchen_hood_wall.jpg" alt="render" width="260"> | <img src="img/hf_05_kitchen_hood_wall.jpg" alt="Higgsfield" width="260"> |
| Kitchen islands | <img src="img/vui_06_kitchen_islands.jpg" alt="Blender" width="260"> | <img src="img/blend_06_kitchen_islands.jpg" alt="render" width="260"> | <img src="img/hf_06_kitchen_islands.jpg" alt="Higgsfield" width="260"> |
| Pantry | <img src="img/vui_07_pantry.jpg" alt="Blender" width="260"> | <img src="img/blend_07_pantry.jpg" alt="render" width="260"> | <img src="img/hf_07_pantry.jpg" alt="Higgsfield" width="260"> |
| Office library | <img src="img/vui_08_office_library.jpg" alt="Blender" width="260"> | <img src="img/blend_08_office_library.jpg" alt="render" width="260"> | <img src="img/hf_08_office_library.jpg" alt="Higgsfield" width="260"> |
| Coffee niche aisle | <img src="img/vui_09_coffee_niche_aisle.jpg" alt="Blender" width="260"> | <img src="img/blend_09_coffee_niche_aisle.jpg" alt="render" width="260"> | <img src="img/hf_09_coffee_niche_aisle.jpg" alt="Higgsfield" width="260"> |
| Butler's pantry | <img src="img/vui_10_butlers_pantry.jpg" alt="Blender" width="260"> | <img src="img/blend_10_butlers_pantry.jpg" alt="render" width="260"> | <img src="img/hf_10_butlers_pantry.jpg" alt="Higgsfield" width="260"> |
| Laundry main | <img src="img/vui_11_laundry_main.jpg" alt="Blender" width="260"> | <img src="img/blend_11_laundry_main.jpg" alt="render" width="260"> | <img src="img/hf_11_laundry_main.jpg" alt="Higgsfield" width="260"> |
| Mud room | <img src="img/vui_12_mud_room.jpg" alt="Blender" width="260"> | <img src="img/blend_12_mud_room.jpg" alt="render" width="260"> | <img src="img/hf_12_mud_room.jpg" alt="Higgsfield" width="260"> |
| Powder 1 | <img src="img/vui_13_powder_1.jpg" alt="Blender" width="260"> | <img src="img/blend_13_powder_1.jpg" alt="render" width="260"> | <img src="img/hf_13_powder_1.jpg" alt="Higgsfield" width="260"> |
| Primary en suite | <img src="img/vui_14_primary_ensuite.jpg" alt="Blender" width="260"> | <img src="img/blend_14_primary_ensuite.jpg" alt="render" width="260"> | <img src="img/hf_14_primary_ensuite.jpg" alt="Higgsfield" width="260"> |
| Powder 2 | <img src="img/vui_15_powder_2.jpg" alt="Blender" width="260"> | <img src="img/blend_15_powder_2.jpg" alt="render" width="260"> | <img src="img/hf_15_powder_2.jpg" alt="Higgsfield" width="260"> |
| Upper powder | <img src="img/vui_16_upper_powder.jpg" alt="Blender" width="260"> | <img src="img/blend_16_upper_powder.jpg" alt="render" width="260"> | <img src="img/hf_16_upper_powder.jpg" alt="Higgsfield" width="260"> |
| Upper laundry | <img src="img/vui_17_upper_laundry.jpg" alt="Blender" width="260"> | <img src="img/blend_17_upper_laundry.jpg" alt="render" width="260"> | <img src="img/hf_17_upper_laundry.jpg" alt="Higgsfield" width="260"> |
| Upper en suite | <img src="img/vui_18_upper_ensuite.jpg" alt="Blender" width="260"> | <img src="img/blend_18_upper_ensuite.jpg" alt="render" width="260"> | <img src="img/hf_18_upper_ensuite.jpg" alt="Higgsfield" width="260"> |
| Bath 3 | <img src="img/vui_19_bath_3.jpg" alt="Blender" width="260"> | <img src="img/blend_19_bath_3.jpg" alt="render" width="260"> | <img src="img/hf_19_bath_3.jpg" alt="Higgsfield" width="260"> |
| Bath 4 | <img src="img/vui_20_bath_4.jpg" alt="Blender" width="260"> | <img src="img/blend_20_bath_4.jpg" alt="render" width="260"> | <img src="img/hf_20_bath_4.jpg" alt="Higgsfield" width="260"> |
| Bath 5 | <img src="img/vui_21_bath_5.jpg" alt="Blender" width="260"> | <img src="img/blend_21_bath_5.jpg" alt="render" width="260"> | <img src="img/hf_21_bath_5.jpg" alt="Higgsfield" width="260"> |
| Bath 6 | <img src="img/vui_22_bath_6.jpg" alt="Blender" width="260"> | <img src="img/blend_22_bath_6.jpg" alt="render" width="260"> | <img src="img/hf_22_bath_6.jpg" alt="Higgsfield" width="260"> |
| Bath 7 | <img src="img/vui_23_bath_7.jpg" alt="Blender" width="260"> | <img src="img/blend_23_bath_7.jpg" alt="render" width="260"> | <img src="img/hf_23_bath_7.jpg" alt="Higgsfield" width="260"> |
| Bath 8 | <img src="img/vui_24_bath_8.jpg" alt="Blender" width="260"> | <img src="img/blend_24_bath_8.jpg" alt="render" width="260"> | <img src="img/hf_24_bath_8.jpg" alt="Higgsfield" width="260"> |
| Bar niche | <img src="img/vui_25_bar_niche.jpg" alt="Blender" width="260"> | <img src="img/blend_25_bar_niche.jpg" alt="render" width="260"> | <img src="img/hf_25_bar_niche.jpg" alt="Higgsfield" width="260"> |
| Bar kitchenette | <img src="img/vui_26_bar_kitchenette.jpg" alt="Blender" width="260"> | <img src="img/blend_26_bar_kitchenette.jpg" alt="render" width="260"> | <img src="img/hf_26_bar_kitchenette.jpg" alt="Higgsfield" width="260"> |

## What is drawn, and what is assumed

Cabinet sizes, counters, niches, mirrors, room widths and ceiling heights are taken 1:1 from the DDS CAD file; fixtures come from the Canva selections. The DDS package covers cabinetry only, so the overall footprint of the house was traced from the concept deck’s plan thumbnails at an assumed front width. When an architect’s plan set is available, the model is rebuilt from it and every image on this page is re-rendered.

**From the DWG:** cabinet runs, depths, heights, openings · **From the concept deck:** finishes, fixtures, camera views · **From Canva:** lighting and mirror products · **Assumed:** whole-house footprint scale

*Work Official LLC · 3D build, renders and presentation images produced September 2026.*
