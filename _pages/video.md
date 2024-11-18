---
title: "Video"
layout: default
excerpt: "RT2 Lab"
sitemap: false
permalink: /video/
---

# Ray-tracing GPU Technology

<iframe width="560" height="315" src="https://www.youtube.com/embed/h_AQ77AicD4?si=_XTByVeXvjnwCfl6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/GpM-S8eVCNs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Sound-tracing Technology

<iframe width="560" height="315" src="https://www.youtube.com/embed/AOFmVFOSHE8?si=lrmkR3B9mwxGdT-z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Sound-Tracing
- Sound-Tracing은 3차원 지형 데이터 상에서 음원과 청취자 간의 소리 전파 경로를 추적하여 현실감 있는 3차원 사운드를 생성하는 기법으로, 다양한 음향 특성을 반영하여 보다 정교하고 몰입감 있는 오디오 환경을 제공한다.
- 본 데모는 다양한 재료(예: 나무, 금속, 콘크리트, 타일, 등)이 포함된 3차원 지형데이터에서 수행되는 Sound-Tracing을 보여준다. 현실감을 높이기 위해 반사, 회절, 흡수, 잔향 그리고 도플러와 같은 특수 음향 효과를 지원하고 있으며 다수 개의 음원들에 대하여 실시간 Mixing을 지원한다.
- Sound-Tracing은 다양한 플랫폼에서 사용할수 있도록 설계되어 PC, VR 기기, 스마트폰 등 다양한 환경에서 구현이 가능하다.

# Real-time AI Technology Denoising

<iframe width="560" height="315" src="https://www.youtube.com/embed/ItnCp5CjGwo?si=QWgWsiSQwqMLiqR-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/RxHUl1sTF5Y?si=v7vM5rYE2flf1Vml" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Denoising
- 실시간 Path-tracing을 위해서는 픽셀당 샘플링 수(Sample Per Pixel)를 대폭 줄여야 하며, 이 과정에서 Noise가 매우 심해지기 때문에 실시간 Denoising기술이 필수적이다.
- 본 데모는 고해상도 이미지 렌더링시 발생하는 노이즈를 AI 신경망을 활용해서 실시간으로 제거하는 것을 보여준다. Benchmark(위)San-miguel, (아래)Bathroom는 1spp환경에서 렌더링한 scenes의 노이즈를 제거한다.
- 데모에 활용한 AI 신경망은 U-net 신경망을 경량화(23M -> 1M) 하고, 노이즈 제거에 특화될 수 있도록 구축하였다.

# Real-time AI Technology Dehazing

<iframe width="560" height="315" src="https://www.youtube.com/embed/xxd2XIxQL4Y?si=BAdHCckw_ueC21YF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


<iframe width="560" height="315" src="https://www.youtube.com/embed/Yv-fr1wOTtg?si=4BpJ291ouhx-5yhC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Dehazing
- 카메라를 통해 획득된 이미지(영상)는 해무, 황사, 안개와 같은 날씨 상황으로 인해 노이즈가 심화 될 수 있다. 노이즈로 손상된 이미지는 시각적인 품질 저하 뿐만 아니라, 이를 활용하는 애플리케이션의 학습 및 성능에 부정적인 영향을 끼치므로 우선적으로 해결해야 하는 중요한 문제이다.
- 본 데모는 카메라를 통해 획득한 안개 이미지의 노이즈를 AI 신경망을 활용해서 제거하는 것을 보여준다. AI신경망은 안개로 인해 소실된 정보를 복원하고, 안개를 제거한다.
- 데모에 활용한 AI 신경망은 U-net 신경망을 경량화(23M -> 1M) 하고, 안개 제거에 특화될 수 있도록 구축하였다.

# 사운드 트레이싱 기술을 실시간으로 처리하는 기술

<iframe width="560" height="315" src="https://youtu.be/22G3sJWjt3w?si=QNu8-a6CGerkT2Pv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>