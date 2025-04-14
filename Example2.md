|Condition Stubs|Action Stubs|
|-|-|
|It's raining|Put on raincoat|
|I have to go out|leave raincoat in closet
||go outside|

Number of Rule:
```math
$2^{N} =2^2 = 4$
```

#### Decision table
||Title|-|1|2|3|4|
|-|-|-|-|-|-|-|
|1|It is raining|-|Y|Y|N|N|
|2|I have to go out|-|Y|N|Y|N|
|-|-|-|-|-|-|-|
|1|Put on raincoat|-|X|
|2|Leave raincoat in closet|-||X|X|X|
|3|go outside|-|X||X||

#### The simplified decision table
||Title|-|1|2|3|
|-|-|-|-|-|-|
|1|It is raining|-|Y|N|-|
|2|I have to go out|-|Y|Y|N|
|-|-|-|-|-|-|-|
|1|Put on raincoat|-|X|
|2|Leave raincoat in closet|-||X|X|
|3|go outside|-|X|X||