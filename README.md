For COSC3500 I have developed a simple raytracing algorithm. While the code cannot be published *publically* until the course is completed.

# Features

Primitives:
- Quads
- Planes
- Boxes
- Spheres

Materials:
- Lambertians
- Metallics (with reflection)
- Dielectrics (with refraction, via snells law)
- Plastics (combined reflection and lambertian)

Automatic white balancing and reinhard tone mapping.

Optimisations include the slab method for box intersections, bounding volume heirarchies, upscaling, adaptive sampling rates and light steering.

# Gallery
<img width="1290" height="1299" alt="image" src="https://github.com/user-attachments/assets/a824e5bd-f883-4812-8f21-59ad1850cd85" />
<img width="1273" height="868" alt="image" src="https://github.com/user-attachments/assets/7bf1a9cd-31a3-46af-adce-adc59688ddac" />
<img width="1193" height="1264" alt="image" src="https://github.com/user-attachments/assets/d9e1bdaa-cfd9-4c4b-8ae0-05619da7d862" />
<img width="1319" height="1302" alt="image" src="https://github.com/user-attachments/assets/e33a0a58-7694-4271-8076-89f9fb4a2769" />


# Benchmarking
I have also developed a full benchmarking utility, which produces in depth analysis like the below:
<img width="1154" height="1197" alt="image" src="https://github.com/user-attachments/assets/8addb643-d01f-4f82-9002-b5505be58aad" />
<img width="2580" height="1346" alt="image" src="https://github.com/user-attachments/assets/29bfd857-5c58-4193-9cc1-3a97ff8d2b69" />
