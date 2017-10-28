---
layout: '[layout]'
title: postName
date: 2017-10-28 20:11:28
tags:
---

# 王双双

32424234

```java
package com.lxt.chenfengjy.applicationtest;

import android.app.Application;

/**
 * Created by Lxt ChenFengJY on 2017/3/22.
 * good good study ，day day up
 */

public class MyApplication extends Application {
    private long exitTime = 0;
    private static MyApplication instance;

    public long getExitTime() {
        return exitTime;
    }

    public void setExitTime(long exitTime) {
        this.exitTime = exitTime;
    }

    @Override
    public void onCreate() {
        super.onCreate();
        instance = this;
    }

    public static MyApplication getInstance() {
        return instance;
    }
}

```

> 回海口海口海口海口海口



