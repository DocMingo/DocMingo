<h1 align="center"> 
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&width=400&lines=嗨👋，我是+DocMingo%0A点云算法工程师" alt="Typing SVG" />
  </a>
</h1>

<p align="left">
  <a href="https://github.com/DocMingo?tab=repositories">
    <img alt="VS Code" 
         src="https://img.shields.io/badge/Editor-VS_Code-007ACC?logo=visualstudiocode&logoColor=white&style=flat">
  </a>
  <a href="https://github.com/DocMingo?tab=repositories">
    <img alt="Visual Studio" 
         src="https://img.shields.io/badge/IDE-Visual_Studio-5C2D91?logo=visualstudio&logoColor=white&style=flat">
  </a>
    <a href="https://github.com/DocMingo">
    <img alt="GitHub Hits" src="https://img.shields.io/github/followers/DocMingo?label=Follow%20%40DocMingo&style=social">
  </a>
</p>


<!-- 3D技术栈徽章 -->
<p align="center">
  <img src="https://img.shields.io/badge/-LiDAR点云%20渲染-8A2BE2?logo=opencv&logoColor=white">
  <img src="https://img.shields.io/badge/-3DGS-FF8C00?logo=blender&logoColor=white">
  <img src="https://img.shields.io/badge/-PCL-00BFFF?logo=pointcloud&logoColor=white">
</p>


<p align="center">
    <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXFuZzB2ZWJ1Y2U0bGt6cHM1dzh5MHVxNHEwdTc2ZHVscjQ3eXdldyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/FylQRlWk1dr8aHhdWH/giphy.gif" width="300" />
</p>

<!-- 双卡片统计布局 -->
<p align="center">
  <a href="https://github.com/DocMingo">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=DocMingo&count_private=true&theme=radical&show_icons=true&include_all_commits=true" alt="Stats" />
  </a>
  <a href="https://github.com/DocMingo">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DocMingo&layout=compact&theme=radical&langs_count=6&hide=html,css" alt="Top Langs" />
  </a>
</p>

<h3 align="center">🛠 技术栈</h3>
<p align="center">
  <img src="https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white" title="C++" hspace="4">
  <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" title="Python" hspace="4">
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white" title="PyTorch" hspace="4">
  <img src="https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white" title="OpenCV" hspace="4">
  <img src="https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white" title="Docker" hspace="4">
  <img src="https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black" title="Linux" hspace="4">
  <img src="https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white" title="Git" hspace="4">
  <img src="https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white" title="PostgreSQL" hspace="4">
</p>


<h3 align="center">🚀 开发规划</h3>

<div align="center">
  <table>
    <tr>
      <td><img src="https://img.shields.io/badge/■_HyperCloud_Engine-000000?style=for-the-badge&logo=point-cloud&logoColor=00FFFF" width="300"></td>
      <td>
        <ul align="left">
          <li>⏳ 实时LiDAR点云处理</li>
          <li>🧊 体素化压缩算法 (CR > 10:1)</li>
          <li>⚡ cuda加速可视化</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><img src="https://img.shields.io/badge/■_Neural_GS_Renderer-000000?style=for-the-badge&logo=matrix&logoColor=FF00FF" width="300"></td>
      <td>
        <ul align="left">
          <li>🧠 可微分3D高斯喷射</li>
          <li>🌌 神经辐射场混合架构</li>
          <li>🔄 高性能实时渲染</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

<h4 align="center">▍技术指标 | Tech Specs</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Compute_Units-256_CUDA_Cores-blueviolet">  
  <img src="https://img.shields.io/badge/Precision-FP16_Accel-9cf">
  <img src="https://img.shields.io/badge/Latency-<2ms-success">
</p>

<details>
<summary><b>🛰️ 底层架构 | Core Architecture</b></summary>

```mermaid
graph LR
  A[LiDAR Raw Data] --> B[Octree Spatial Partition]
  B --> C[Neural Voxelization]
  C --> D{Hybrid Render Pipeline}
  D --> E[PointCloud Render]
  D --> F[Gaussian Splatting]
  D --> G[NeRF Synthesis]
