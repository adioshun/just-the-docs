---
layout: default
title: RoI Filtering
nav_order: 4
has_children: true
permalink: /docs/400-roi-filter
---



RoI Filtering
======================

본 챕터에서는 point cloud 필터링 기법 중 관심 영역(RoI:Region of Interesting)을 추출하는 RoI Filtering에 대하여 다루고 있습니다.

PCL에서는 Conditional Filter, PassThrough filter란 이름으로 해당 기능을 제공 하고 있습니다.

> PCL에서는 Conditional Filter를 Noise제거용으로 소개 하고 있지만, RoI추출에 좀더 유용한것 같아 RoI 추출 기법으로 분류 하였습니다.
> Conditional filter는 PassThrough 대비 필터링 조건을 좀더 풍부하게 지정 할 수 있습니다.
