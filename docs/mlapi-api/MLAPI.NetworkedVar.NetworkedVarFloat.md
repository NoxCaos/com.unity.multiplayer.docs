---  
id: MLAPI.NetworkedVar.NetworkedVarFloat  
title: MLAPI.NetworkedVar.NetworkedVarFloat  
---

<div class="markdown level0 summary" markdown="1">

A NetworkedVar that holds floats and support serialization

</div>

<div class="markdown level0 conceptual" markdown="1">

</div>

<div class="inheritance" markdown="1">

##### Inheritance

<div class="level0" markdown="1">

System.Dynamic.ExpandoObject

</div>

<div class="level1" markdown="1">

System.Dynamic.ExpandoObject

</div>

<div class="level2" markdown="1">

System.Dynamic.ExpandoObject

</div>

</div>

<div markdown="1" classs="implements">

##### Implements

<div markdown="1">

INetworkedVar

</div>

</div>

<div class="inheritedMembers" markdown="1">

##### Inherited Members

<div markdown="1">

NetworkedVar\<Single\>.isDirty"

</div>

<div markdown="1">

NetworkedVar\<Single\>.Settings"

</div>

<div markdown="1">

NetworkedVar\<Single\>.LastSyncedTime"

</div>

<div markdown="1">

NetworkedVar\<Single\>.OnValueChanged"

</div>

<div markdown="1">

NetworkedVar\<Single\>.Value"

</div>

<div markdown="1">

NetworkedVar\<Single\>.ResetDirty()"

</div>

<div markdown="1">

NetworkedVar\<Single\>.IsDirty()"

</div>

<div markdown="1">

NetworkedVar\<Single\>.CanClientRead(UInt64)"

</div>

<div markdown="1">

NetworkedVar\<Single\>.WriteDelta(Stream)"

</div>

<div markdown="1">

NetworkedVar\<Single\>.CanClientWrite(UInt64)"

</div>

<div markdown="1">

NetworkedVar\<Single\>.ReadDelta(Stream, Boolean)"

</div>

<div markdown="1">

NetworkedVar\<Single\>.SetNetworkedBehaviour(NetworkedBehaviour)"

</div>

<div markdown="1">

NetworkedVar\<Single\>.ReadField(Stream)"

</div>

<div markdown="1">

NetworkedVar\<Single\>.WriteField(Stream)"

</div>

<div markdown="1">

NetworkedVar\<Single\>.GetChannel()"

</div>

<div markdown="1">

Object.Equals(Object)

</div>

<div markdown="1">

Object.Equals(Object, Object)

</div>

<div markdown="1">

Object.GetHashCode()

</div>

<div markdown="1">

Object.GetType()

</div>

<div markdown="1">

Object.MemberwiseClone()

</div>

<div markdown="1">

Object.ReferenceEquals(Object, Object)

</div>

<div markdown="1">

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax [MLAPI_NetworkedVar_NetworkedVarFloat_syntax]

    [Serializable]
    public class NetworkedVarFloat : NetworkedVar<float>, INetworkedVar

## Constructors 

### NetworkedVarFloat() [MLAPI_NetworkedVar_NetworkedVarFloat__ctor]

<div class="markdown level1 summary" markdown="1">

</div>

<div class="markdown level1 conceptual" markdown="1">

</div>

#### Declaration [declaration]

    public NetworkedVarFloat()

### NetworkedVarFloat(NetworkedVarSettings) [MLAPI_NetworkedVar_NetworkedVarFloat__ctor_MLAPI_NetworkedVar_NetworkedVarSettings_]

<div class="markdown level1 summary" markdown="1">

</div>

<div class="markdown level1 conceptual" markdown="1">

</div>

#### Declaration [declaration-1]

    public NetworkedVarFloat(NetworkedVarSettings settings)

#### Parameters [parameters]

| Type                 | Name     | Description |
|----------------------|----------|-------------|
| NetworkedVarSettings | settings |             |

### NetworkedVarFloat(NetworkedVarSettings, Single) [MLAPI_NetworkedVar_NetworkedVarFloat__ctor_MLAPI_NetworkedVar_NetworkedVarSettings_System_Single_]

<div class="markdown level1 summary" markdown="1">

</div>

<div class="markdown level1 conceptual" markdown="1">

</div>

#### Declaration [declaration-2]

    public NetworkedVarFloat(NetworkedVarSettings settings, float value)

#### Parameters [parameters-1]

| Type                 | Name     | Description |
|----------------------|----------|-------------|
| NetworkedVarSettings | settings |             |
| System.Single        | value    |             |

### NetworkedVarFloat(Single) [MLAPI_NetworkedVar_NetworkedVarFloat__ctor_System_Single_]

<div class="markdown level1 summary" markdown="1">

</div>

<div class="markdown level1 conceptual" markdown="1">

</div>

#### Declaration [declaration-3]

    public NetworkedVarFloat(float value)

#### Parameters [parameters-2]

| Type          | Name  | Description |
|---------------|-------|-------------|
| System.Single | value |             |

### Implements [implements]

<div markdown="1">

INetworkedVar

</div>