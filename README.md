# Structural-Design-and-Analysis-of-a-Reinforced-Flyover-Bridge
This project involved the structural design and analysis of a proposed 120-metre reinforced flyover bridge in Minna, Niger State. The bridge employed a 30-metre post-tensioned concrete girder system. The work included comprehensive modelling of all structural components: pile foundation, pile cap, pier, pier cap, bearings, slab, pavement structure, and parapet. Structural performance checks were carried out to assess deflection limits, verify shear capacity, and ensure the adequacy of reinforcement detailing.
![Image](https://github.com/user-attachments/assets/b7aca4b1-def2-46c3-9a34-9bbe0017c5bb?raw=true)
### Bridge Model
# Objectives
1. To model the proposed flyover with all structural members to include:
- pile foundation,
- pile cap
- pier
- pier cap
- bearing
- slab
- pavement structure
- parapet
2. To check for deflection, if the shear force is adequate, and if the reinforcement is adequate 
# Types of Loading Applied
## Fatigue Loads
Fatigue loads are repeated traffic loads used to check that bridge parts won't crack or fail over time from long-term use.
## HA Loading & HB Loading
These represent normal and abnormal traffic load models applied to the bridge.
## Traffic Types
Normal Traffic on the Bridge and	Abnormal Traffic
Includes UD (Uniformly Distributed Load) & PL (Point Load)	Includes heavy abnormal loads
## Finite Element Model (FEM)
This ntroduces the finite element modelling concept. It includes the deck height and width definition.
# Model Setup
-	Next → Click Isoview
-	Coordinate directions:
o	Y ↑
o	Z →
o	X ↓
1. Structure Type
-	Structure → RC / Slab Bridge → Click
(This likely means choosing the bridge type in MIDAS.)
2. Interface Setup
-	"Have an interface" (likely meaning use the bridge wizard interface)
3. Directions & Load Inputs
-	Longitudinal
-	Traverse
-	Loads
4. Model → Material
-	Open Model → Material
-	Click Add
5. Material Design Setup
-	"Material design → Type of design (standard – C50?)"
-	“ΔB → 5.46” (possibly width or section parameter
6. Material Selection
-	Material: Concrete C50, C35, OK
(You wrote BSOT, may refer to standard code.)

7. Plate Element Size
-	“Size of plate element = span 1.0m”
8. Skew Angle
-	“Skew (°) angle for girders”
(Define skew angle if the bridge is not orthogonal.)
9. Deck Thickness (t)
-	“t = thickness of deck, from drawings.”
10. Difference Between Abutments / Bearings
-	“a1 = distance between center of bearing to the edge of deck.”
11. Dimensions Written
-	t1 = 0.12
-	φ11 = 0.3
-	a2 = 0.3
(likely parameters for deck or reinforcement spacing)
12. Elastic Link Length
-	“Elastic link length = 1.0”
(Used for bearing representation.)
13. Move to Traverse
-	Continue with traverse modelling settings.
14. b1 → Girder to Deck Dimension
-	b1 = girder to deck = 0.975 m
15. Choose the Line Type
-	Choose line (Type 1)
-	Type 1, 2, 3 (options listed)
16. b2, b3, b5, b6, b7, b1 Values
You wrote several parameters:
-	b2 → b5
-	b3 → b2
-	b4 → 1
-	b5 → 7.3
-	b6 → 2.1
-	b7 → 1
-	b1 → 0.2 next
(These are likely distances between girders or deck offsets.)
17. a-Values (Bearing / Deck Distances)
-	a₁ = 0.3 m
-	a₂ = 0.3 m
-	a₃ = 0.0 m
-	“bearing 6”
(Indicating bearing locations or girder spacing input.)
18. Loads Section
a. Moving Load
-	Moving load → BS (British Standard)
-	Pavement (G₁) = 0.1
-	“Mean = 20”
b. C-Beam Load
-	C-beam load = 400 × 800
(likely dimensions or load magnitude)
19. Perform Analysis
Go to:
-	Perform analysis → Results → Force
Check:
-	Plate forces
-	Moments
20. Components (Display Settings)
-	Type of Display → Contour values
-	Legend
-	Deforms
21. Pre-processing Mode (CFT)
-	“Preprocessing mode (CFT)”
(CFT likely means Composite Frame Tool or a mode for checking results.)
22. Load Combinations Use Load Combinations
-	Click Envelope (to see combined effect)
-	Maximum
-	Cb max factor envelope
-	Then Apply
a) Thickness of the Deck
-	“The thickness of the deck has an expansion of 30?”
(This appears to be a question about thermal expansion or construction tolerance.)
b) Small t — Meaning and When to Apply
-	“Small t – meaning and when to apply it.”
(Possibly referring to deck thickness or cover thickness in design.)
3) ‘lthy’ is a₃? 0
-	Possibly: “Length is a₃ = 0
23. Expansion Space
-	“8 cm space between the abutment and the girders for expansion.”
24. Prefabricated Slab
-	“Prefabricated slab on the girders, which serves as a cover between two girders made of R.C.”
25. Difference Between Types (Type 1, 2, etc.)
-	Difference between Type 1, 2, 3
-	“t₁ is b₁ → b₃, b₄”
o	This means t₁ is related to b₁, b₃, b₄ dimensions.
26. Number of Girders
-	“n = number of girders = 1”
27. Difference Between Longitudinal & Traverse
-	This line indicates understanding the difference between:
o	Longitudinal direction
o	Transverse direction
28. Check Load Cases / Load Combinations
-	"Check load cases/combinations"
29. Pre-processing Mode
-	“Pre-processing mode (for indicating analysis effect)”
(This is likely referring to switching MIDAS into pre-processing view to inspect loads, nodes, elements.)
