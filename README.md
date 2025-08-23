# 🎨 3D Gaussian Splatting Style & Geometry Transfer

> **3D Gaussian Splatting**에서 **style transfer**와 함께 **geometry**도 변화하는 연구 (~ing)

---

## 📖 About

본 연구는 기존 3D style transfer 방법과 달리, 스타일 이미지의 특성에 따라 **3D 장면의 기하학적 구조까지 함께 변형**시키는 새로운 접근법을 제안.

---

## 🎯 Results

### 📷 **Original Scene**

<table>
<tr>
<td width="50%">

![Original Scene](images/original.jpg)
**Original museum dinosaur scene**

</td>
<td width="50%">

![Depth Map](images/depth_map.jpg)
**Depth map of the original scene**

</td>
</tr>
</table>

---

### 🧊 **Cube Style Transfer**

| Reference Style | Result | Depth Map |
|:---:|:---:|:---:|
| ![Style Image](images/style_cube.jpg)<br>*3D colorful cubes pattern* | ![Stylized Result](images/result_cubes.jpg)<br>*Stylized with cube geometry* | ![Result Depth](images/result_depth.jpg)<br>*Geometric transformation* |

---

### 🌊 **Wave Style Transfer** 

| Reference Style | Result | Depth Map |
|:---:|:---:|:---:|
| ![Wave Style](images/style_wave.jpg)<br>*Traditional Japanese wave pattern* | ![Wave Style Result](images/result_wave.jpg)<br>*Organic curved deformation* | ![Wave Depth](images/wave_depth.jpg)<br>*Wave-like transformation* |
