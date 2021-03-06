﻿.. module:: cookie

cookie
====================================

|  cookie
|  源码: `查看 <https://github.com/kissyteam/kissy/tree/master/src/cookie/base.js>`_

    .. note::

        推荐阅读 NCZ 的这篇文章： `HTTP cookies explained <http://www.nczonline.net/blog/2009/05/05/http-cookies-explained/>`_

Module
-----------------------------------------------

  :mod:`cookie`


Methods
-----------------------------------------------

.. function:: get

    | Object **parse** ( name )
    | 获取cookie值
    
    :param String name: cookie的名称

    :returns: {String} - 


.. function:: remove

    | String **stringify** ( name, domain, path, secure )
    | 置空cookie值，并立刻过期
    
    :param String name,: cookie的名称`
    :param String domain: 域`
    :param String path: 路径`
    :param Boolean secure: 安全标志`
		
.. function:: set

    | String **set** ( name, val, expires[, domain, path, secure] )
    | 设置cookie值
    
    :param String name,: cookie的名称`
    :param String val: cookie的值`
    :param number|date expires: 失效时间`
    :param String domain: 域`
    :param String path: 路径`
    :param Boolean secure: 安全标志`
