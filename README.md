> [!WARNING]
> Support for Apple MPS has only been tested in the detection part, not the training part.
>
> Please be careful about using it directly in a production environment. Please carefully review whether the results of the code are correct before you use it in a production environment.

# YOLOv7 with Apple MPS Support

Based on official yolov7 implementation - just added Apple MPS support

Apple MPS (Metal Performance Shader) can significantly improve the speed of models on Apple Silicon (at least on my Apple M1).

To use it, simply write "mps" in the device parameter.

> [!CAUTION]
> Make sure your machine supports MPS acceleration. Do not use MPS acceleration on systems or machines that do not support Apple MPS.
> 
> Check out https://pytorch.org/docs/stable/notes/mps.html for more information.
