# Improved_MikuMikuDance
The improved version of the MMD(MikuMikuDance) which is inspired by others.

This version of the generate is started by animation video(can be also the real-world video), and end by MMD files.

The main difference when we use different started video is the using of Animation GAN.

(Started by animation)

Ani to Real-World GAN->3D pose estimation->single RGB depth estimation->Construct Video Depth estimation->generate the MMD

(Started by real-world, which is similar with openMMD)

3D pose estimation->single RGB depth estimation->Construct Video Depth estimation->generate the MMD
