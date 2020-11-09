# Pss5


## Description
Italian PSS - Detailed PSS.

## Data Model
  - properties:
    - kpe:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Electric power input gain (K).  Typical Value = 0.3. Default: 0.0
    - kf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Frequency/shaft speed input gain (K).  Typical Value = 5. Default: 0.0
    - isfreq:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Selector for Frequency/shaft speed input (IsFreq). true = speed false = frequency. Typical Value = true. Default: False
    - kpss:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : PSS gain (K).  Typical Value = 1. Default: 0.0
    - ctw2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Selector for Second washout enabling (C). true = second washout filter is bypassed false = second washout filter in use. Typical Value = true. Default: False
    - tw1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : First WashOut (T).  Typical Value = 3.5. Default: 0
    - tw2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Second WashOut (T).  Typical Value = 0. Default: 0
    - tl1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lead/lag time constant (T).  Typical Value = 0. Default: 0
    - tl2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lead/lag time constant (T).  Typical Value = 0. Default: 0
    - tl3:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lead/lag time constant (T).  Typical Value = 0. Default: 0
    - tl4:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lead/lag time constant (T).  Typical Value = 0. Default: 0
    - vsmn:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Stabilizer output max limit (V).  Typical Value = -0.1. Default: 0.0
    - vsmx:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Stabilizer output min limit (V).  Typical Value = 0.1. Default: 0.0
    - tpe:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Electric power filter time constant (T).  Typical Value = 0.05. Default: 0
    - pmm:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum power PSS enabling (P).  Typical Value = 0.25. Default: 0.0
    - deadband:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Stabilizer output dead band (DeadBand).  Typical Value = 0. Default: 0.0
    - vadat:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: :  Default: False