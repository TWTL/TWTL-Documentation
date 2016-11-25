# Engine Feature: Network

TWTL Doc 015

엔진의 네트워크 기능에 대해 서술합니다.

## Overview

인터넷 공간에서 웹 페이지를 방문하기 위해서는 웹페이지 도메인 주소를 통해 DNS 서버에서 목표주소(destination)에 해당하는 IP 주소를
획득, 이를 통해 해당 IP 주소 서버에 방문하여 페이지를 전송 받아야 합니다. 최근 기승을 부리는 여러 악성코드들은 웹페이지에 방문하는
것 자체만으로 사용자에게 영향을 끼칠 수 있는 능력을 갖추고 있습니다. 또한 사용자가 의도한
방문 뿐만 아니라 악성코드를 통한 웹페이지 접속이 이루어질 수도 있습니다. 따라서 시스템이 접근하려는 IP 주소를 확인, 이 IP 주소가
사용자에게 해로운 웹페이지인지를 판단하여 알리는 일이 필요할 것입니다. TWTL 엔진의 네트워크 기능에 대해 정의합니다.

## 방식

TBD

## 대상

TBD