# FlatBuffersFeatureMatrix

|Root               |[FlatBuffers](https://github.com/google/flatbuffers)|[flatcc](https://github.com/dvidelabs/flatcc)|[FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift)|
|-------------------|----------------------------------------------------|---------------------------------------------|-------------------------------------------------------------|
|Table|+|+|+|
|Union|-|-|-|
|Vector|-|-|-|
|Struct|-|-|-|
|Multiple Roots|-|-|-|

|Table              |[FlatBuffers](https://github.com/google/flatbuffers)|[flatcc](https://github.com/dvidelabs/flatcc)|[FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift)|
|-------------------|----------------------------------------------------|---------------------------------------------|-------------------------------------------------------------|
|field as Scalar|+|+|+|
|field as Boolean Scalar|+|+|+|
|field as String|+|+|+|
|field as Enum|+|+|+|
|field as Struct|+|+|+|
|field as ref. to Table|+|+|+|
|field as ref. to Union|+|+|+|
|field as ref. to Vector|+|+|+|
|field with custom id|+|+|-|
|field as deprecated|+|+|+|
|field as required|+|+|-|
|field as key|+|+|-|
|field as nested FlatBuffer|+|+|/|
|field with scalar default|+|+|+|
|field with string default|-|-|-|
|field as Bit Flags Enum|+|+|-|
|field with real optional support for Scalars|-|-|-|
|field with ref. to same type of Table|+|+|+|
|Cyclic Graph detection and managment|-|-|-|

|Struct              |[FlatBuffers](https://github.com/google/flatbuffers)|[flatcc](https://github.com/dvidelabs/flatcc)|[FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift)|
|--------------------|----------------------------------------------------|---------------------------------------------|-------------------------------------------------------------|
|field as Scalar|+|+|+|
|field as Boolean Scalar|+|+|+|
|field as String|-|-|-|
|field as Enum|+|+|+|
|field as Struct|+|+|-|
|field as Struct with same type|-|-|-|
|field as ref. to Table|-|-|-|
|field as ref. to Union|-|-|-|
|field as ref. to Vector|-|-|-|

|Vector              |[FlatBuffers](https://github.com/google/flatbuffers)|[flatcc](https://github.com/dvidelabs/flatcc)|[FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift)|
|--------------------|----------------------------------------------------|---------------------------------------------|-------------------------------------------------------------|
|containnig Scalar|+|+|+|
|containnig Boolean Scalar|+|+|+|
|containnig Enum|+|+|+|
|containnig Struct|+|+|+|
|containnig ref. to String|+|+|+|
|containnig ref. to Table|+|+|+|
|containnig ref. to Union|+|+|+|
|containnig ref. to Vector|-|-|-|

|Enum              |[FlatBuffers](https://github.com/google/flatbuffers)|[flatcc](https://github.com/dvidelabs/flatcc)|[FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift)|
|------------------|----------------------------------------------------|---------------------------------------------|-------------------------------------------------------------|
|starting with 0|+|+|+|
|not starting with 0|-|-|+|
|defined with random order|-|-|-|
|explicit type|+|+|+|
|infered type|-|-|-|

|Union              |[FlatBuffers](https://github.com/google/flatbuffers)|[flatcc](https://github.com/dvidelabs/flatcc)|[FlatBuffersSwift](https://github.com/mzaks/FlatBuffersSwift)|
|------------------|----------------------------------------------------|---------------------------------------------|-------------------------------------------------------------|
|one table part of multiple unions|?|?|+|
