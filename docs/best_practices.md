<!-- markdownlint-disable MD041 -->
<!-- Copyright 2015-2021 LunarG, Inc. -->
[![Khronos Vulkan][1]][2]

[1]: https://vulkan.lunarg.com/img/Vulkan_100px_Dec16.png "https://www.khronos.org/vulkan/"
[2]: https://www.khronos.org/vulkan/

# Best Practices Validation

Best Practices Validation is implemented in the `VK_LAYER_KHRONOS_validation layer`. When enabled, the Best Practices Object is
intended to highlight potential performance issues, questionable usage patterns, common mistakes, and items not specifically prohibited
by the Vulkan specification but that may lead to application problems.

Best Practices will ideally be run periodically along with normal validation checks so that issues may be addressed in early stages of development.

Best Practices Validation settings can be set by configuring the Validation Layer. These settings are described in
[khronos_validation_layer.html](https://vulkan.lunarg.com/doc/sdk/latest/windows/khronos_validation_layer.html#user-content-layer-details).

The specific areas covered by this layer are currently tracked in the
[Best Practices Project](https://github.com/KhronosGroup/Vulkan-ValidationLayers/projects/1).
Requests for additional checks can be requested by creating a Github issue.
