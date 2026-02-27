.. meta::
    :description: ROCm-LLMExt compatibility matrix
    :keywords: ROCm, LLM, AMD, Instinct, GPU, computer, graphics, python, toolkit, accelerated, verl, Stanford Megatron-LM, Megablocks, llama.cpp, ray, FlashInfer

.. _llmext-compat-matrix:

**************************************************************************************
ROCm-LLMExt compatibility matrix
**************************************************************************************

.. |docker-icon| raw:: html

   <i class="fab fa-docker"></i>

Use the following matrix to view the ROCm-LLMExt compatibility and system requirements across releases:

+----------------------+--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
| ROCm-LLMExt version  | Ubuntu | ROCm version | Python version | PyTorch version    | AMD Instinct GPU | Component                                    | Docker Hub                         |
+======================+========+==============+================+====================+==================+==============================================+====================================+
| 25.09                | 24.04  | 6.4.1        | 3.12.9         | 2.7.1              | MI300X           | `FlashInfer 0.2.5                            | |docker-icon| `rocm/flashinfer     |
|                      |        |              |                |                    |                  | <https://rocm.docs.amd.com/projects/         | <https://hub.docker.com/r/rocm/    |
|                      |        |              |                |                    |                  | flashinfer/en/docs-25.09/install/            | flashinfer/tags?name=              |
|                      |        |              |                |                    |                  | flashinfer-install.html>`__                  | flashinfer-0.2.5_rocm6>`__         |
+                      +--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
|                      | 24.04, | 7.0.0,       | N/A            | N/A                | MI325X,          | `llama.cpp b6356                             | |docker-icon| `rocm/llama.cpp      |
|                      | 22.04  | 6.4.3,       |                |                    | MI300X,          | <https://rocm.docs.amd.com/projects/         | <https://hub.docker.com/r/rocm/    |
|                      |        | 6.4.2,       |                |                    | MI210            | llama-cpp/en/docs-25.09/install/             | llama.cpp/tags?name=               |
|                      |        | 6.4.1        |                |                    |                  | llama-cpp-install.html>`__                   | llama.cpp-b6356>`__                |
+----------------------+--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
| 25.08                | 24.04  | 6.4.1        | 3.12.10        | 2.6.0+git684f6f2   | MI300X,          | `Ray 2.48.0.post0                            | |docker-icon| `rocm/ray            |
|                      |        |              |                |                    | MI210            | <https://rocm.docs.amd.com/projects/         | <https://hub.docker.com/r/rocm/    |
|                      |        |              |                |                    |                  | ray/en/docs-25.08/install/                   | ray/tags?name=ray-2.48>`__         |
|                      |        |              |                |                    |                  | ray-install.html>`__                         |                                    |
+                      +--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
|                      | 24.04  | 6.4.0        | N/A            | N/A                | MI300X,          | `llama.cpp b5997                             | |docker-icon| `rocm/llama.cpp      |
|                      |        |              |                |                    | MI210            | <https://rocm.docs.amd.com/projects/         | <https://hub.docker.com/r/rocm/    |
|                      |        |              |                |                    |                  | llama-cpp/en/docs-25.08/install/             | llama.cpp/tags?name=               |
|                      |        |              |                |                    |                  | llama-cpp-install.html>`__                   | llama.cpp-b5997>`__                |
+                      +--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
|                      | 24.04  | 6.3.0        | 3.12.9         | 2.4.0              | MI300X           | `Megablocks 0.7.0                            | |docker-icon| `rocm/megablocks     |
|                      |        |              |                |                    |                  | <https://rocm.docs.amd.com/projects/         | <https://hub.docker.com/r/rocm/    |
|                      |        |              |                |                    |                  | megablocks/en/docs-25.08/install/            | megablocks/tags?name=              |
|                      |        |              |                |                    |                  | megablocks-install.html>`__                  | megablocks-0.7.0>`__               |
+                      +--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
|                      | 24.04  | 6.3.0        | 3.12.9         | 2.4.0              | MI300X           | `Stanford Megatron-LM 85f95ae                | |docker-icon| `rocm/stanford-      |
|                      |        |              |                |                    |                  | <https://rocm.docs.amd.com/projects/         | megatron-lm                        |
|                      |        |              |                |                    |                  | stanford-megatron-lm/en/docs-25.08/install/  | <https://hub.docker.com/r/rocm/    |
|                      |        |              |                |                    |                  | stanford-megatron-lm-install.html>`__        | stanford-megatron-lm/tags?name=    |
|                      |        |              |                |                    |                  |                                              | stanford-megatron-lm85f95ae>`__    |
+                      +--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
|                      | 20.04  | 6.2.0        | 3.9.19         | 2.5.0              | MI300X           | `verl 0.3.0.post0                            | |docker-icon| `rocm/verl           |
|                      |        |              |                |                    |                  | <https://rocm.docs.amd.com/projects/         | <https://hub.docker.com/r/rocm/    |
|                      |        |              |                |                    |                  | verl/en/docs-25.08/install/                  | verl/tags?name=                    |
|                      |        |              |                |                    |                  | verl-install.html>`__                        | name=verl-0.3.0>`__                |
+----------------------+--------+--------------+----------------+--------------------+------------------+----------------------------------------------+------------------------------------+
