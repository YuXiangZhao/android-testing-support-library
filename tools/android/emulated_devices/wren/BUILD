#Description:
#   Android Wear Wren device.
#

load("//tools/android/emulated_devices:macro/make_device.bzl", "make_device")

package(default_visibility = ["//visibility:public"])

# TODO: Arm emulators are timing out.

make_device(
    name = "wren",
    boot_properties = {
        "ro.product.manufacturer": "ASUS",
        "ro.product.model": "ASUS ZenWatch 2",
        "ro.product.name": "wren",
    },
    cache = 32,
    # TODO(b/30588599): Remove this once uma emulators can be built.
    emulator_types = ["qemu"],
    horizontal_resolution = 280,
    max_api = 25,
    min_api = 20,
    ram = 512,
    screen_density = 280,
    system_image_flavors = ["wear"],
    vertical_resolution = 280,
    vm_heap = 48,
)
