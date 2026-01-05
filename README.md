# Attention:
- This package is under active development. 
- Currently, package is unusuable.
- It will be released

#  Anonymous NPU booster Library (previously: Intel® NPU Acceleration Library)

The Anonymous NPU booster library is a Python library designed to boost the efficiency of your applications by leveraging the power of the Intel Neural Processing Unit (NPU) to perform high-speed computations on compatible hardware.

## Intel NPU

The Intel NPU is an AI accelerator integrated into Intel Core Ultra processors, characterized by a unique architecture comprising compute acceleration and data transfer capabilities. Its compute acceleration is facilitated by Neural Compute Engines, which consist of hardware acceleration blocks for AI operations like Matrix Multiplication and Convolution, alongside Streaming Hybrid Architecture Vector Engines for general computing tasks.

To optimize performance, the NPU features DMA engines for efficient data transfers between system memory and a managed cache, supported by device MMU and IOMMU for security isolation. The NPU's software utilizes compiler technology to optimize AI workloads by directing compute and data flow in a tiled fashion, maximizing compute utilization primarily from scratchpad SRAM while minimizing data transfers between SRAM and DRAM for optimal performance and power efficiency.

Some useful links

- Intel AI PC ([link](https://www.intel.com/content/www/us/en/products/docs/processors/core-ultra/ai-pc.html?wapkw=NPU))
- Intel Core Ultra Processor line ([link](https://www.intel.com/content/www/us/en/products/docs/processors/core-ultra/core-ultra-series-1-product-brief.html?wapkw=NPU))
- AI Acceleration and NPU explained ([video](https://www.youtube.com/watch?v=QSzNoX0qplE))
