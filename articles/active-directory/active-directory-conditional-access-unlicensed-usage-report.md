---
title: Informe de uso sin licencia | Microsoft Docs
description: "El informe de uso sin licencia ayuda a identificar usuarios sin licencia que utilizan características de Azure AD de pago,"
services: active-directory
documentationcenter: 
author: MarkusVi
manager: mtillman
ms.assetid: 92138f43-9528-4c8a-b834-66a47da476e3
ms.service: active-directory
ms.workload: identity
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.date: 01/15/2018
ms.author: markvi
ms.openlocfilehash: 8bcd814ee7b7bfc158e62ad26e6cc23781f5352d
ms.sourcegitcommit: 384d2ec82214e8af0fc4891f9f840fb7cf89ef59
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 01/16/2018
---
# <a name="unlicensed-usage-report"></a>Informe de uso sin licencia
El informe de uso sin licencia ayuda a identificar usuarios sin licencia que utilizan características de Azure AD de pago, lo que permite hacer un mejor uso de las licencias que se han adquirido e identificar en qué momento se necesitan más licencias. 

El informe muestra el uso activo de las características de pago en los últimos 30 días. 

## <a name="report-structure"></a>Estructura del informe
| Nombre de la columna | DESCRIPCIÓN |
|:--- |:--- |
| Usuario sin licencia |Nombre del usuario |
| Característica |El nombre de la característica. Por ejemplo: acceso condicional |
| Aplicación a la que se accede |El nombre de la aplicación a la que se accede con la característica. Por ejemplo: Office 365 SharePoint Online |

> [!NOTE]
> Si se ha eliminado una cuenta de usuario, la columna "Usuario sin licencia" se rellenará con un identificador, como 1003000090D8B285
> 
> 

## <a name="conditional-access-feature"></a>Características de acceso condicional
A los usuarios sin licencia se les marcará cuando accedan a un servicio al que se haya aplicado la directiva de acceso condicional, siempre que no tengan una licencia de Azure AD Premium. 

Esto se aplica a las directivas de MFA/ubicación, así como a las directivas de dispositivos que usan Intune.

## <a name="see-also"></a>Otras referencias
* [Protección del acceso a Office 365 y otras aplicaciones conectadas a Azure Active Directory](active-directory-conditional-access-azure-portal.md)
* [Introducción al acceso condicional a Azure AD](active-directory-conditional-access-azure-portal-get-started.md) 

