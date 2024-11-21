Latest Logs From Latest Build
==============================

Generated On: 2024-11-21 18:14:31 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/hardikdagar7/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-21_18:09:00] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-21_18:09:03] STEP 2: Create topics started

  [INFO 2024-11-21_18:09:14] STEP 2: Completed

  [INFO 2024-11-21_18:09:20] STEP 3: producing data started

  [INFO 2024-11-21_18:09:22] STEP 4: Preprocessing started

  [INFO 2024-11-21_18:09:23] MQTT connection established...

  [INFO 2024-11-21_18:09:24] STEP 4: Preprocessing started

  [INFO 2024-11-21_18:09:25] STEP 7: Visualization started

  [INFO 2024-11-21_18:09:31] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-21_18:09:35] STEP 9: Starting privateGPT

  [INFO 2024-11-21_18:09:40] STEP 8: Starting docker push for: hardikdagar0207/testtwo-7042-amd64

  [INFO 2024-11-21_18:09:47] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --gpus all --env PORT=8001 --env GPU=1 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-with-gpu-nvidia-amd64

  [INFO 2024-11-21_18:10:02] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit ea2f272d0b81 hardikdagar0207/testtwo-7042-amd64 - message=0

  [INFO 2024-11-21_18:14:26] STEP 8: Successfully ran Docker push: docker push hardikdagar0207/testtwo-7042-amd64 - message=0

  [INFO 2024-11-21_18:14:31] STEP 10: Started to build the documentation

  [INFO 2024-11-21_18:14:31] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


