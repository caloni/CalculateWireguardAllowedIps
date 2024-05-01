# Multiple peers Wireguard calculation

Wireguard does not support overlapping allowed ips for multiple peers. To cover all possible ips excluding others for secondary peers some calculation is needed to mount the allowed ips list derived from `0.0.0.0`.