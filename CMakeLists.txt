# Copyright (C) 2011 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT (lua-digest-crc32lua NONE)
CMAKE_MINIMUM_REQUIRED (VERSION 2.6)
INCLUDE ( dist.cmake )

install_lua_module ( digest.crc32lua module/lmod/digest/crc32lua.lua )
install_data ( COPYRIGHT )

