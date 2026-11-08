# 🪷 Lily Bloom: Math-Made 3D Flower Animation

**Plant a thought. Wait 13 seconds.**

A bouquet of Oriental lilies, grown entirely from code. No photos, no 3D models, no Blender. Every petal, leaf and stem is calculated with math and drawn frame by frame using Python.

---

## 🎬 What You Get

A 13-second vertical video (1080 × 1920, 30 fps) where the bouquet builds itself from a glowing wireframe into a fully lit, blooming flower while the camera slowly rises and circles around it. 

## ✨ Highlights

- 🌸 Three blooming lilies with ruffled, recurved petals and tiny raised spots
- 🌿 Arching stems, 15 leaves and 2 flower buds
- 🌼 Six stamens with pollen anthers and a three-lobed pistil in each flower
- 💡 Custom lighting with soft glow through the petals and waxy highlights
- 🎥 Smooth camera movement, floating pollen and a "specimen label" overlay
- ⚡ Parallel rendering across your CPU cores

## 🧰 Built With

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| NumPy | Geometry and lighting math |
| OpenCV | Drawing, blur and video output |
| FFmpeg (optional) | Higher-quality video encoding |

## 📂 Files

```
python-3D-lily-animation/
├── lily.py        # the full animation script
└── README.md
```

## 🚀 How to Run

**1. Get the code**

```bash
git clone https://github.com/surbhisingh-07/python-3D-lily-animation.git
cd python-3D-lily-animation
```

**2. Install the libraries**

```bash
pip install numpy opencv-python
```

**3. (Optional) Quick preview.** Makes 4 still images in seconds:

```bash
python lily.py --preview
```

**4. Render the full video**

```bash
python lily.py
```

Your video appears in the same folder as `lily_3d_botanical_animation.mp4`.

> ⏳ Rendering takes about 10 to 30 minutes depending on your computer. Lower `WIDTH` and `HEIGHT` at the top of the script for a faster test.

## 🎛️ Make It Your Own

Open `lily.py` and try changing:

- `WIDTH`, `HEIGHT`, `DURATION` to change the video size and length
- `color_variant` to switch petal colors
- `flowers_spec` to move or resize the flowers

## 🧠 What You Can Learn Here

- How 3D shapes are built from curves and grids of points
- How lighting makes flat colors look real
- How a camera turns 3D space into a 2D picture
- How to turn code into a finished video

## 🩷 About

This project is my experiment in turning imagination into motion using only Python. It was first shared as a coding reel, so if you found it there, welcome!

## ⭐ Support

If this made you smile, give the repo a star. It really helps!
