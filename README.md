Download Link: https://assignmentchef.com/product/solved-csci376-assignment-1-opencl-basics
<br>
Write an OpenCL program that does the following:

<ul>

 <li>Allow the user to enter whether he/she wants to use a CPU or a GPU device. Based on the user’s selection, search the system for all CPU or GPU devices. (Note that some systems have multiple CPUs and GPUs).

  <ul>

   <li>mark)</li>

  </ul></li>

 <li>Based on the user’s choice, display the following information for each CPU/GPU device that is available on the system: o Name of the platform(s) that support that device

  <ul>

   <li>Device type – CPU or GPU</li>

  </ul></li>

</ul>

(hint: CL_DEVICE_TYPE_CPU or CL_DEVICE_TYPE_GPU) o Device name

<ul>

 <li>Number of compute units</li>

</ul>

(hint: CL_DEVICE_MAX_COMPUTE_UNITS) o Maximum work group size

(hint: CL_DEVICE_MAX_WORK_GROUP_SIZE) o Maximum work item sizes

(hint: CL_DEVICE_MAX_WORK_ITEM_SIZES) o Global memory size

(hint: CL_DEVICE_GLOBAL_MEM_SIZE)




<ul>

 <li>Based on the devices available, allow the user to select one device. Check whether the device supports the cl_khr_icd extension (hint: CL_DEVICE_EXTENSIONS). Create a context and a command queue for that device.</li>

</ul>







<ul>

 <li>Read the program source code from the provided “source.cl” file and build the program. Display whether or not the program built successfully and display the program build log (display the build log even if the program built successfully. Note: for some compilers, the build log will be empty if successful).</li>

</ul>




<ul>

 <li>Find and display the number of kernels in the program. Create kernels from the program and display all the kernel function names.</li>

</ul>