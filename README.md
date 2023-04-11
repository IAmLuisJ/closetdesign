# [closetGPT.com](https://www.closetdesign.vercel.com)

This project generates designs of your closet with AI.

## How it works

It uses an ML model called [ControlNet](https://github.com/lllyasviel/ControlNet) to generate variations of rooms. This application gives you the ability to upload a photo of any room, which will send it through this ML Model using a Next.js API route, and return your generated room. The ML Model is hosted on [Replicate](https://replicate.com) and [Upload](https://upload.io) is used for image storage.
