---
title: Use shared VM images to create a scale set in Azure CLI
description: Learn how to use the Azure CLI to create shared VM images to use for deploying virtual machine scale sets in Azure.
author: cynthn
ms.service: virtual-machine-scale-sets
ms.subservice: shared-image-gallery
ms.topic: conceptual
ms.date: 05/06/2019
ms.author: cynthn
ms.reviewer: mimckitt

---
# Create and use shared images for virtual machine scale sets with the Azure CLI 2.0

**Applies to:** :heavy_check_mark: Linux VMs :heavy_check_mark: Windows VMs :heavy_check_mark: Uniform scale sets

When you create a scale set, you specify an image to be used when the VM instances are deployed. A [Shared Image Gallery](../virtual-machines/shared-image-galleries.md) simplifies custom image sharing across your organization. Custom images are like marketplace images, but you create them yourself. Custom images can be used to bootstrap configurations such as preloading applications, application configurations, and other OS configurations. 

The Shared Image Gallery lets you share your images with others. Choose which images you want to share, which regions you want to make them available in, and who you want to share them with. 


[!INCLUDE [virtual-machines-common-shared-images-cli](../../includes/virtual-machines-common-shared-images-cli.md)]


## Next steps

Create an image version from a [VM](../virtual-machines/image-version-vm-cli.md), or a [managed image](../virtual-machines/image-version-managed-image-cli.md).

For more information about Shared Image Galleries, see the [Overview](../virtual-machines/shared-image-galleries.md). If you run into issues, see [Troubleshooting shared image galleries](../virtual-machines/troubleshooting-shared-images.md).
