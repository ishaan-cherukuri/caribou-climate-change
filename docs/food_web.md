!!! note

    Please refrain from using dark mode as it does not properly work on this diagram.

```mermaid
 graph BT;
    classDef c1 fill:#9ceaf0,stroke:#333 stroke-width:20px, font-size:22.5pt;

    classDef c2 fill:#f7c6f7,stroke:#333 stroke-width:20px, font-size:22.5pt;

    Phytoplankton["`Phytoplanton -> **Autotroph** `"]
    Mussel["`Mussel -> **Heterotroph** `"]
    Sea_Otter["`Sea Otter -> **Heterotroph** `"]
    Orca["`Orca -> **Heterotroph** `"]
    Ringed_Seal["`Ringed Seal -> **Heterotroph** `"]
    Artic_Cod["`Artic Cod -> **Heterotroph** `"]
    Krill["`Krill -> **Heterotroph** `"]
    Caribou_Moss["`Caribou Moss -> **Autotroph** `"]
    Caribou["`Caribou -> **Heterotroph** `"]
    Polar_Bear["`Polar Bear -> **Heterotroph** `"]
    Lichen["`Lichen -> **Autotroph** `"]
    Artic_Fox["`Artic Fox -> **Heterotroph** `"]
    Artic_Wolf["`Artic_Wolf -> **Heterotroph** `"]
    Lemming["`Lemming -> **Heterotroph** `"]
    Snowy_Owl["`Snowy Owl -> **Heterotroph** `"]
    Artic_Willow["`Artic_Willow -> **Autotroph** `"]

    Phytoplankton:::c1-->Mussel
    Phytoplankton-->Krill
    Mussel:::c2-->Sea_Otter:::c2
    Sea_Otter-->Orca
    Krill:::c2-->Artic_Cod
    Artic_Cod:::c2-->Orca
    Artic_Cod:::c2-->Ringed_Seal
    Ringed_Seal:::c2-->Orca:::c2
    Ringed_Seal:::c2-->Polar_Bear:::c2
    Caribou_Moss:::c1-->Caribou
    Lichen:::c1-->Caribou
    Lichen-->Lemming
    Artic_Willow:::c1-->Lemming
    Caribou:::c2-->Polar_Bear
    Lemming:::c2-->Artic_Fox
    Lemming:::c2-->Artic_Wolf:::c2
    Lemming:::c2-->Snowy_Owl
    Caribou:::c2-->Artic_Wolf
    Artic_Fox:::c2-->Artic_Wolf
    Snowy_Owl:::c2-->Artic_Fox
    Snowy_Owl:::c2-->Artic_Wolf
```


