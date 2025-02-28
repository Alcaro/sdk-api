---
UID: NE:d3d12.D3D12_GRAPHICS_STATES
title: D3D12_GRAPHICS_STATES (d3d12.h)
description: Defines flags that specify states related to a graphics command list. Values can be bitwise OR'd together.
old-location: direct3d12\d3d12_graphics_states.htm
tech.root: direct3d12
ms.assetid: 261585A3-CDF1-4559-9E14-9EE710F1D8D9
ms.date: 12/05/2018
ms.keywords: D3D12_GRAPHICS_STATES, D3D12_GRAPHICS_STATES enumeration, D3D12_GRAPHICS_STATE_COMPUTE_ROOT_SIGNATURE, D3D12_GRAPHICS_STATE_DESCRIPTOR_HEAP, D3D12_GRAPHICS_STATE_GRAPHICS_ROOT_SIGNATURE, D3D12_GRAPHICS_STATE_IA_INDEX_BUFFER, D3D12_GRAPHICS_STATE_IA_PRIMITIVE_TOPOLOGY, D3D12_GRAPHICS_STATE_IA_VERTEX_BUFFERS, D3D12_GRAPHICS_STATE_NONE, D3D12_GRAPHICS_STATE_OM_BLEND_FACTOR, D3D12_GRAPHICS_STATE_OM_DEPTH_BOUNDS, D3D12_GRAPHICS_STATE_OM_RENDER_TARGETS, D3D12_GRAPHICS_STATE_OM_STENCIL_REF, D3D12_GRAPHICS_STATE_PIPELINE_STATE, D3D12_GRAPHICS_STATE_PREDICATION, D3D12_GRAPHICS_STATE_RS_SCISSOR_RECTS, D3D12_GRAPHICS_STATE_RS_VIEWPORTS, D3D12_GRAPHICS_STATE_SAMPLE_POSITIONS, D3D12_GRAPHICS_STATE_SO_TARGETS, D3D12_GRAPHICS_STATE_VIEW_INSTANCE_MASK, d3d12/D3D12_GRAPHICS_STATES, d3d12/D3D12_GRAPHICS_STATE_COMPUTE_ROOT_SIGNATURE, d3d12/D3D12_GRAPHICS_STATE_DESCRIPTOR_HEAP, d3d12/D3D12_GRAPHICS_STATE_GRAPHICS_ROOT_SIGNATURE, d3d12/D3D12_GRAPHICS_STATE_IA_INDEX_BUFFER, d3d12/D3D12_GRAPHICS_STATE_IA_PRIMITIVE_TOPOLOGY, d3d12/D3D12_GRAPHICS_STATE_IA_VERTEX_BUFFERS, d3d12/D3D12_GRAPHICS_STATE_NONE, d3d12/D3D12_GRAPHICS_STATE_OM_BLEND_FACTOR, d3d12/D3D12_GRAPHICS_STATE_OM_DEPTH_BOUNDS, d3d12/D3D12_GRAPHICS_STATE_OM_RENDER_TARGETS, d3d12/D3D12_GRAPHICS_STATE_OM_STENCIL_REF, d3d12/D3D12_GRAPHICS_STATE_PIPELINE_STATE, d3d12/D3D12_GRAPHICS_STATE_PREDICATION, d3d12/D3D12_GRAPHICS_STATE_RS_SCISSOR_RECTS, d3d12/D3D12_GRAPHICS_STATE_RS_VIEWPORTS, d3d12/D3D12_GRAPHICS_STATE_SAMPLE_POSITIONS, d3d12/D3D12_GRAPHICS_STATE_SO_TARGETS, d3d12/D3D12_GRAPHICS_STATE_VIEW_INSTANCE_MASK, direct3d12.d3d12_graphics_states
ms.topic: enum
f1_keywords:
- d3d12/D3D12_GRAPHICS_STATES
dev_langs:
- c++
req.header: d3d12.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- HeaderDef
api_location:
- D3D12.h
api_name:
- D3D12_GRAPHICS_STATES
targetos: Windows
req.typenames: D3D12_GRAPHICS_STATES
req.redist: 
ms.custom: 19H1
---

# D3D12_GRAPHICS_STATES enumeration


## -description


Defines flags that specify states related to  a graphics command list. Values can be bitwise OR'd together.


## -enum-fields




### -field D3D12_GRAPHICS_STATE_NONE

Specifies no state.


### -field D3D12_GRAPHICS_STATE_IA_VERTEX_BUFFERS

Specifies the state of the vertex buffer bindings on the input assembler stage.


### -field D3D12_GRAPHICS_STATE_IA_INDEX_BUFFER

Specifies the state of the index buffer binding on the input assembler stage.


### -field D3D12_GRAPHICS_STATE_IA_PRIMITIVE_TOPOLOGY

Specifies the state of the primitive topology value set on the input assembler stage.


### -field D3D12_GRAPHICS_STATE_DESCRIPTOR_HEAP

Specifies the state of the currently bound descriptor heaps.


### -field D3D12_GRAPHICS_STATE_GRAPHICS_ROOT_SIGNATURE

Specifies the state of the currently set graphics root signature.


### -field D3D12_GRAPHICS_STATE_COMPUTE_ROOT_SIGNATURE

Specifies the state of the currently set compute root signature.


### -field D3D12_GRAPHICS_STATE_RS_VIEWPORTS

Specifies the state of the viewports bound to the rasterizer stage.


### -field D3D12_GRAPHICS_STATE_RS_SCISSOR_RECTS

Specifies the state of the scissor rectangles bound to the rasterizer stage.


### -field D3D12_GRAPHICS_STATE_PREDICATION

Specifies the predicate state.


### -field D3D12_GRAPHICS_STATE_OM_RENDER_TARGETS

Specifies the state of the render targets bound to the output merger stage.


### -field D3D12_GRAPHICS_STATE_OM_STENCIL_REF

Specifies the state of the reference value for depth stencil tests set on the output merger stage.


### -field D3D12_GRAPHICS_STATE_OM_BLEND_FACTOR

Specifies the state of the blend factor set on the output merger stage.


### -field D3D12_GRAPHICS_STATE_PIPELINE_STATE

Specifies the state of the pipeline state object.


### -field D3D12_GRAPHICS_STATE_SO_TARGETS

Specifies the state of the buffer views bound to the stream output stage.


### -field D3D12_GRAPHICS_STATE_OM_DEPTH_BOUNDS

Specifies the state of the depth bounds set on the output merger stage.


### -field D3D12_GRAPHICS_STATE_SAMPLE_POSITIONS

Specifies the state of the sample positions.


### -field D3D12_GRAPHICS_STATE_VIEW_INSTANCE_MASK

Specifies the state of the view instances mask.

