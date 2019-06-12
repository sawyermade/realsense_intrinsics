# Intel Realsense Intrinsics
## D435
### Color
width: 640, height: 480, ppx: 327.69, ppy: 242.552, fx: 618.2, fy: 618.74, model: Brown Conrady, coeffs: [0, 0, 0, 0, 0]
#### Python Code
```
width, height = 640, 480
fx = 618.74
fy = 618.74
cx, cy = 327.69, 242.552
scale = 0.0010000000474974513 
```
#### Python Dictionary
```
camera_settings: {
	"name": "realsense_d435",
	"width": 640,
	"height": 480,
	"fx": 385.567,
	"fy": 385.567,
	"cx": 318.557,
	"cy": 243.841
}
```
### Depth
Depth:
width: 640, height: 480, ppx: 318.557, ppy: 243.841, fx: 385.567, fy: 385.567, model: Brown Conrady, coeffs: [0, 0, 0, 0, 0], scale: 0.0010000000474974513

### Run python code and print them
```
git clone https://github.com/sawyermade/realsense_intrinsics.git
cd realsense_intrinsics
python3 rs_intrinsics.py
```
