# Сессионный проект. MEPHI. РЕД ОС 8

-**Уникальный номер:** М265872
-**ОС:** РЕД ОС 8.0.3
-**GitHub:** Viktor3491

|Раздел|Что сделано|Артефакты|
|------|-----------|---------|
|1| DHCP, hostname mephi-2026.domain.local, ping | ping.out |
|2| dnf update, nginx, libcap-ng-utils, tcpdump через rpm | dnf.out |
|3| loop-устройство, ext4 MEPHI_WEB, /mephi-web | fstab |
|4| Автозапуск nginx, journalctl | journalctl.out |
|5.1| DAC: user1/2/3 (5501-5503), curators (4444), ACL | - |
|5.2| tcpdump через cap_net_raw, cap_net_admin | getcap.out |
|5.3| SELinux Enforcing, httpd_sys_content_t | getenforce.out, stat.out |
|6| nologin для кураторов, minlen=12, PASS_MAX_DAYS=90 | pwquality.conf |
|7| index.html, curl | curl.out |
|8| Публикация | mephi-screenshot.png |
