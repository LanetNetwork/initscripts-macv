Place these scripts in `/etc/sysconfig/network-scripts` on your
RedHat/CentOS/Fedora system.

Sample configuration for a `macvtap` interface:

	DEVICE="test"
	TYPE="macv"
	DEVICETYPE="Ethernet"
	BOOTPROTO="static"
	IPADDR="1.2.3.4"
	NETMASK="255.255.255.0"
	ONBOOT="yes"
	NM_CONTROLLED="no"

	MACV_TEAM="team0"
	MACV_VLAN="101"
	MACV_TYPE="macvtap"
	MACV_MODE="bridge"
	MACV_MAC="00:11:22:33:44:55"

License
=======

Derived from initscripts-macvlan

Copyright (C) 2014 Lars Kellogg-Stedman

Adopted by Oleksandr Natalenko &lt;o.natalenko@lanet.ua&gt;

Copyright (C) 2016 Lanet Network

Based on Network Interface Configuration System
Copyright (c) 1996-2009 Red Hat, Inc. all rights reserved.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

