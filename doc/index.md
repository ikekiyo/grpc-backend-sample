# サンプルAPI仕様書
<a name="top"></a>

## インデックス
- [API仕様](#API仕様)

  - [helloworld.proto](#helloworld.proto)
      - [HelloReply](#helloworld.HelloReply)
      - [HelloRequest](#helloworld.HelloRequest)
  
  
  
      - [Greeter](#helloworld.Greeter)
  

  - [helloworld2.proto](#helloworld2.proto)
      - [HelloReply2](#helloworld2.HelloReply2)
      - [HelloRequest2](#helloworld2.HelloRequest2)
  
  
  
      - [Greeter2](#helloworld2.Greeter2)
  

- [スカラー値型](#スカラー値型)

## API仕様


<a name="helloworld.proto"></a>
<p align="right"><a href="#top">Top</a></p>

### helloworld.proto



<a name="helloworld.HelloReply"></a>

#### HelloReply



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| message | [string](#string) |  |  |






<a name="helloworld.HelloRequest"></a>

#### HelloRequest



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| name | [string](#string) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="helloworld.Greeter"></a>

#### Greeter


| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| SayHello | [HelloRequest](#helloworld.HelloRequest) | [HelloReply](#helloworld.HelloReply) |  |
| SayHello2 | [HelloRequest](#helloworld.HelloRequest) | [HelloReply](#helloworld.HelloReply) |  |

 <!-- end services -->



<a name="helloworld2.proto"></a>
<p align="right"><a href="#top">Top</a></p>

### helloworld2.proto



<a name="helloworld2.HelloReply2"></a>

#### HelloReply2



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| message | [string](#string) |  |  |






<a name="helloworld2.HelloRequest2"></a>

#### HelloRequest2



| Field | Type | Label | Description |
| ----- | ---- | ----- | ----------- |
| name | [string](#string) |  |  |





 <!-- end messages -->

 <!-- end enums -->

 <!-- end HasExtensions -->


<a name="helloworld2.Greeter2"></a>

#### Greeter2


| Method Name | Request Type | Response Type | Description |
| ----------- | ------------ | ------------- | ------------|
| SayHello3 | [HelloRequest2](#helloworld2.HelloRequest2) | [HelloReply2](#helloworld2.HelloReply2) |  |

 <!-- end services -->



