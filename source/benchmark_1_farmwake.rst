.. _benchmark_1_farmwake:


.. raw:: html

    <style> .red {color:red} </style>

.. role:: red


.. raw:: html

    <style> .blue {color:blue} </style>

.. role:: blue


Benchmark 1: Wind Farm Wake
================================

Case Study
----------------------

The goal of this benchmark is to simulate the area around the King Plains and Armadillo Flats wind farms on 24 August 2023. As stated above, the size of the modeling domain is left to the participants, however, we recommend to include both wind farms to be able to capture their interaction during the day to simulate.

The figure below shows the observed wind speed, wind direction and lidar-derived TKE at AWAKEN site A1 on the selected case study. The vertical dashed lines show local sunset (left) and sunrise (right).

.. figure:: images/a1_lidar.jpg


Validation Objectives
---------------------

The goal of this benchmark is to evaluate the models' ability to accurately capture:

- Wind farm wake characteristics
    - Momentum deficit
    - Turbulence increase

- Impacts on downstream wind plants
    - Power generation

- Impacts on downstream environment
    - Temperature

- Effects of inflow conditions
    - Wind speed
    - Wind direction
    - Turbulence
    - Atmospheric stability
    - Shear and veer

- Effects of geometry
    - Plant layout
    - Turbine size
    - Topography


Simulation Tools
----------------

All simulation tools are welcome to participate in this benchmark. This includes, but it is not limited to:

- Mesoscale models
- Steady-state analytical models
- Dynamic wake meandering-type models
- Engineering models
- Large-eddy simulation (LES), both coupled to mesoscale or run at the microscale only
- Reynolds-averaged Navier–Stokes (RANS) simulations
- Machine learning models

Guidelines
-----------------------

- Participation in the benchmark is open to all participants of IEA Wind Task 57 “JAM”.
- Simulation tools should be used to the limit of their capabilities. 2D, steady-state solutions will be accepted for low-fidelity models. 3D, time-varying solutions will be expected from mid-to-high fidelity models.
- The choice of domain size, grid spacing, timestep, and other model configuration parameters is left to the discretion of the participants.
- Multi-model benchmark results will be published in journal article and co-authored by all participants who choose to release their results and participate in the publication effort.
- All provided results must observe the variable definitions and units as explicitly defined in the :ref:`glossary<glossary>`.


Coordinate System
-----------------------------

All benchmark analyses should use a coordinate system centered on King Plains' turbine H05 (lat = 36.364708, lon = -97.405487), with the x-axis following longitude, and the y-axis following latitude, as shown in the image below:

.. figure:: images/coordinate_system.png

Z (vertical height) should be calculated in meters above the terrain.


Team
----

A large team of researchers have participated to the preparation of this benchmark. The benchmark lead is Nicola Bodini (nicola.bodini@nrel.gov), feel free to reach out to him with questions!




