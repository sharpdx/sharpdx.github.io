---
layout: wiki
title: D3DCompiler API
---

> This page is automatically generated from the assembly documentation.
> 
> It provides links between managed types and methods in the `SharpDX.D3DCompiler` assembly and the original documentation of the [`D3DCompiler`](https://msdn.microsoft.com/en-us/library/windows/desktop/dd607340.aspx) API on MSDN.

The Direct3D shader compiler API.

- <a href='#api-Enumerations'>Enumerations</a>
- <a href='#api-Structures'>Structures</a>
- <a href='#api-Interfaces'>Interfaces</a>

# <a id="api-Enumerations">Enumerations</a>

Managed | Native
----- | --------------------------------
`ConstantBufferFlags` | [`D3D_SHADER_CBUFFER_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728729.aspx)<p>Values that identify the indended use of a constant-data buffer.</p>
`ConstantBufferType` | [`D3D_CBUFFER_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728722.aspx)<p>Values that identify the intended use of constant-buffer data.</p>
`DisassemblyFlags` | `D3DCOMPILE_DISASM_FLAGS`<p>No documentation.</p>
`EffectFlags` | `D3DCOMPILE_EFFECT_FLAGS`<p>No documentation.</p>
`IncludeType` | [`D3D_INCLUDE_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728723.aspx)<p>Values that indicate the location of a shader #include file.</p>
`InputPrimitive` | [`D3D_PRIMITIVE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728725.aspx)<p>Values that indicate how the pipeline interprets geometry or hull shader input primitives.</p>
`ParameterFlags` | [`D3D_PARAMETER_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280475.aspx)<p>Indicates semantic flags for function parameters.</p>
`RegisterComponentMaskFlags` | `???`<p>No documentation.</p>
`RegisterComponentType` | [`D3D_REGISTER_COMPONENT_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728727.aspx)<p>Values that identify the data types that can be stored in a register.</p>
`ResourceReturnType` | [`D3D_RESOURCE_RETURN_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728728.aspx)<p>Values that identify the return type of a resource.</p>
`SecondaryDataFlags` | `D3DCOMPILE_SECDATA_FLAGS`<p>No documentation.</p>
`ShaderBytecodePart` | [`D3D_BLOB_PART`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728720.aspx)<p>Values that identify parts of the content of an arbitrary length data buffer.</p>
`ShaderFlags` | [`D3DCOMPILE_SHADER_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476209.aspx)<p>Describes a shader.</p>
`ShaderInputFlags` | [`D3D_SHADER_INPUT_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728730.aspx)<p>Values that identify shader-input options.</p>
`ShaderInputType` | [`D3D_SHADER_INPUT_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728731.aspx)<p>Values that identify resource types that can be bound to a shader and that are reflected as part of the resource description for the shader.</p>
`ShaderRequiresFlags` | `D3DCOMPILE_SHADER_REQUIRES_FLAGS`<p>No documentation.</p>
`ShaderVariableClass` | [`D3D_SHADER_VARIABLE_CLASS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728733.aspx)<p>Values that identify the class of a shader variable.</p>
`ShaderVariableFlags` | [`D3D_SHADER_VARIABLE_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728734.aspx)<p>Values that identify information about a shader variable.</p>
`ShaderVariableType` | [`D3D_SHADER_VARIABLE_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728735.aspx)<p>Values that identify various data, texture, and buffer types that can be assigned to a shader variable.</p>
`ShaderVersion` | [`D3D11_SHADER_VERSION_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476214.aspx)<p>Indicates shader type.</p>
`StripFlags` | [`D3DCOMPILER_STRIP_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/dd607325.aspx)<p>Strip flag options.</p>
`SystemValueType` | [`D3D_NAME`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728724.aspx)<p>Values that identify shader parameters that use system-value semantics.</p>
`TessellatorDomain` | [`D3D_TESSELLATOR_DOMAIN`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728737.aspx)<p>Values that identify domain options for tessellator data.</p>
`TessellatorOutputPrimitive` | [`D3D_TESSELLATOR_OUTPUT_PRIMITIVE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728738.aspx)<p>Values that identify output primitive types.</p>
`TessellatorPartitioning` | [`D3D_TESSELLATOR_PARTITIONING`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728739.aspx)<p>Values that identify partitioning options.</p>

# <a id="api-Structures">Structures</a>

Managed | Native
----- | --------------------------------
`ConstantBuffer` | [`ID3D11ShaderReflectionConstantBuffer`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476591.aspx)<p>This shader-reflection interface provides access to a constant buffer.</p>
`ConstantBufferDescription` | [`D3D11_SHADER_BUFFER_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476208.aspx)<p>Describes a shader constant-buffer.</p>
`FunctionDescription` | [`D3D11_FUNCTION_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280416.aspx)<p>Describes a function.</p>
`FunctionParameterReflection` | [`ID3D11FunctionParameterReflection`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280544.aspx)<p>A function-parameter-reflection interface accesses function-parameter info.</p>
`FunctionReflection` | [`ID3D11FunctionReflection`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280546.aspx)<p>A function-reflection interface accesses function info.</p>
`Include` | [`ID3DInclude`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728746.aspx)<p> is an include interface that the user implements to allow an application to call user-overridable methods for opening and closing shader #include files.</p>
`InputBindingDescription` | [`D3D11_SHADER_INPUT_BIND_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476210.aspx)<p>Describes how a shader resource is bound to a shader input.</p>
`LibraryDescription` | [`D3D11_LIBRARY_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280417.aspx)<p>Describes a library.</p>
`ParameterDescription` | [`D3D11_PARAMETER_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280419.aspx)<p>Describes a function parameter.</p>
`ShaderBytecode` | `???`<p>Represents the compiled bytecode of a shader or effect.</p>
`ShaderDescription` | [`D3D11_SHADER_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476209.aspx)<p>Describes a shader.</p>
`ShaderParameterDescription` | [`D3D11_SIGNATURE_PARAMETER_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476215.aspx)<p>Describes a shader signature.</p>
`ShaderReflectionType` | [`ID3D11ShaderReflectionType`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476595.aspx)<p>This shader-reflection interface provides access to variable type.</p>
`ShaderReflectionVariable` | [`ID3D11ShaderReflectionVariable`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476607.aspx)<p>This shader-reflection interface provides access to a variable.</p>
`ShaderTypeDescription` | [`D3D11_SHADER_TYPE_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476212.aspx)<p>Describes a shader-variable type.</p>
`ShaderVariableDescription` | [`D3D11_SHADER_VARIABLE_DESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476213.aspx)<p>Describes a shader variable.</p>

# <a id="api-Interfaces">Interfaces</a>

Managed | Native
----- | --------------------------------
`FunctionLinkingGraph`<ul><li>`CallFunction`</li><li>`CallFunction`</li><li>`CreateModuleInstance`</li><li>`GenerateHlsl`</li><li>`LastError`</li><li>`PassValue`</li><li>`PassValue`</li><li>`PassValueWithSwizzle`</li><li>`SetInputSignature`</li><li>`SetOutputSignature`</li><li>`SetOutputSignature`</li></ul> | [`ID3D11FunctionLinkingGraph`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280535.aspx)<ul><li>[`CallFunction`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280536.aspx)</li><li>[`CallFunction`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280536.aspx)</li><li>[`CreateModuleInstance`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280537.aspx)</li><li>[`GenerateHlsl`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280538.aspx)</li><li>[`GetLastError`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280539.aspx)</li><li>[`PassValue`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280540.aspx)</li><li>[`PassValue`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280540.aspx)</li><li>[`PassValueWithSwizzle`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280541.aspx)</li><li>[`SetInputSignature`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280542.aspx)</li><li>[`SetOutputSignature`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280543.aspx)</li><li>[`SetOutputSignature`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280543.aspx)</li></ul><p>[This documentation is preliminary and is subject to change.</p>
`LibraryReflection`<ul><li>`Description`</li><li>`GetFunctionByIndex`</li></ul> | [`ID3D11LibraryReflection`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280554.aspx)<ul><li>[`GetDesc`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280556.aspx)</li><li>[`GetFunctionByIndex`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280557.aspx)</li></ul><p>A library-reflection interface accesses library info.</p>
`Linker`<ul><li>`AddClipPlaneFromCBuffer`</li><li>`Link`</li><li>`UseLibrary`</li></ul> | [`ID3D11Linker`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280558.aspx)<ul><li>[`AddClipPlaneFromCBuffer`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280559.aspx)</li><li>[`Link`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280560.aspx)</li><li>[`UseLibrary`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280561.aspx)</li></ul><p>A linker interface is used to link a shader module.</p>
`LinkingNode` | [`ID3D11LinkingNode`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280562.aspx)<p>A linking-node interface is used for shader linking.</p>
`Module` | [`ID3D11Module`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280563.aspx)<p>A module interface creates an instance of a module that is used for resource rebinding.</p>
`ModuleInstance`<ul><li>`BindConstantBuffer`</li><li>`BindConstantBufferByName`</li><li>`BindResource`</li><li>`BindResourceAsUnorderedAccessView`</li><li>`BindResourceAsUnorderedAccessViewByName`</li><li>`BindResourceByName`</li><li>`BindSampler`</li><li>`BindSamplerByName`</li><li>`BindUnorderedAccessView`</li><li>`BindUnorderedAccessViewByName`</li></ul> | [`ID3D11ModuleInstance`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280564.aspx)<ul><li>[`BindConstantBuffer`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280565.aspx)</li><li>[`BindConstantBufferByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280566.aspx)</li><li>[`BindResource`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280567.aspx)</li><li>[`BindResourceAsUnorderedAccessView`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280568.aspx)</li><li>[`BindResourceAsUnorderedAccessViewByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280569.aspx)</li><li>[`BindResourceByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280570.aspx)</li><li>[`BindSampler`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280571.aspx)</li><li>[`BindSamplerByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280605.aspx)</li><li>[`BindUnorderedAccessView`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280606.aspx)</li><li>[`BindUnorderedAccessViewByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/dn280607.aspx)</li></ul><p>A module-instance interface is used for resource rebinding.</p>
`ShaderReflection`<ul><li>`BitwiseInstructionCount`</li><li>`ConditionalMoveInstructionCount`</li><li>`ConversionInstructionCount`</li><li>`Description`</li><li>`GeometryShaderSInputPrimitive`</li><li>`GetConstantBuffer`</li><li>`GetConstantBuffer`</li><li>`GetInputParameterDescription`</li><li>`GetOutputParameterDescription`</li><li>`GetPatchConstantParameterDescription`</li><li>`GetResourceBindingDescription`</li><li>`GetResourceBindingDescription`</li><li>`GetThreadGroupSize`</li><li>`GetVariable`</li><li>`InterfaceSlotCount`</li><li>`IsSampleFrequencyShader`</li><li>`MinFeatureLevel`</li><li>`MoveInstructionCount`</li><li>`RequiresFlags`</li></ul> | [`ID3D11ShaderReflection`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476590.aspx)<ul><li>[`GetBitwiseInstructionCount`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476611.aspx)</li><li>[`GetMovcInstructionCount`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476619.aspx)</li><li>[`GetConversionInstructionCount`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476614.aspx)</li><li>[`GetDesc`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476615.aspx)</li><li>[`GetGSInputPrimitive`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476616.aspx)</li><li>[`GetConstantBufferByIndex`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476612.aspx)</li><li>[`GetConstantBufferByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476613.aspx)</li><li>[`GetInputParameterDesc`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476617.aspx)</li><li>[`GetOutputParameterDesc`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476622.aspx)</li><li>[`GetPatchConstantParameterDesc`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476623.aspx)</li><li>[`GetResourceBindingDesc`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476624.aspx)</li><li>[`GetResourceBindingDescByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476625.aspx)</li><li>[`GetThreadGroupSize`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff728742.aspx)</li><li>[`GetVariableByName`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476626.aspx)</li><li>[`GetNumInterfaceSlots`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476621.aspx)</li><li>[`IsSampleFrequencyShader`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476627.aspx)</li><li>[`GetMinFeatureLevel`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476618.aspx)</li><li>[`GetMovInstructionCount`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff476620.aspx)</li><li>[`GetRequiresFlags`](https://msdn.microsoft.com/en-us/library/windows/desktop/jj542458.aspx)</li></ul><p>A shader-reflection interface accesses shader information.</p>

