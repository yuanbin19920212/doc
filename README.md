//sticky-headers-recyclerview
compile 'com.timehop.stickyheadersrecyclerview:library:[latest.version.number]@aar'

//mvp

ext {

    android = [
               compileSdkVersion       : 25,
               buildToolsVersion       : "25.0.2",
               minSdkVersion           : 15,
               targetSdkVersion        : 25,
               versionCode             : 101,
               versionName             : "1.0.1"
    ]

     version = [
                   androidSupportSdkVersion: "25.2.0",
                   retrofitSdkVersion      : "2.3.0",
                   dagger2SdkVersion       : "2.11",
                   butterknifeSdkVersion   : "8.7.0",
                   rxlifecycleSdkVersion   : "1.0",
                   rxlifecycle2SdkVersion   : "2.1.0",
                   espressoSdkVersion      : "2.2.2",
                   canarySdkVersion        : "1.5.1"
        ]

    dependencies = [
                //support
                "appcompat-v7"             : "com.android.support:appcompat-v7:${version["androidSupportSdkVersion"]}",
                "design"                   : "com.android.support:design:${version["androidSupportSdkVersion"]}",
                "support-v4"               : "com.android.support:support-v4:${version["androidSupportSdkVersion"]}",
                "cardview-v7"              : "com.android.support:cardview-v7:${version["androidSupportSdkVersion"]}",
                "annotations"              : "com.android.support:support-annotations:${version["androidSupportSdkVersion"]}",
                "recyclerview-v7"          : "com.android.support:recyclerview-v7:${version["androidSupportSdkVersion"]}",
                 "circleimageview"         :"de.hdodenhof:circleimageview:2.1.0",

                //network
                "retrofit"                 : "com.squareup.retrofit2:retrofit:${version["retrofitSdkVersion"]}",
                "retrofit-converter-gson"  : "com.squareup.retrofit2:converter-gson:${version["retrofitSdkVersion"]}",
                "retrofit-adapter-rxjava"  : "com.squareup.retrofit2:adapter-rxjava:${version["retrofitSdkVersion"]}",
                "retrofit-adapter-rxjava2" : "com.squareup.retrofit2:adapter-rxjava2:${version["retrofitSdkVersion"]}",
                "okhttp3"                  : "com.squareup.okhttp3:okhttp:3.8.1",
                "okhttp-urlconnection"     : "com.squareup.okhttp:okhttp-urlconnection:2.0.0",
                "glide"                    : "com.github.bumptech.glide:glide:3.8.0",
                "picasso"                  : "com.squareup.picasso:picasso:2.5.2",

                //view
                "autolayout"               : "com.zhy:autolayout:1.4.5",
                "butterknife"              : "com.jakewharton:butterknife:${version["butterknifeSdkVersion"]}",
                "butterknife-compiler"     : "com.jakewharton:butterknife-compiler:${version["butterknifeSdkVersion"]}",
                "pickerview"               : "com.contrarywind:Android-PickerView:3.2.5",
                "photoview"                : "com.github.chrisbanes.photoview:library:1.2.3",
                "numberprogressbar"        : "com.daimajia.numberprogressbar:library:1.2@aar",
                "nineoldandroids"          : "com.nineoldandroids:library:2.4.0",
                "paginate"                 : "com.github.markomilos:paginate:0.5.1",
                "vlayout"                  : "com.alibaba.android:vlayout:1.0.9@aar",
                "magicIndicator"           : "com.github.hackware1993:MagicIndicator:1.5.0",
                //rx1
                "rxandroid"                : "io.reactivex:rxandroid:1.2.1",
                "rxjava"                   : "io.reactivex:rxjava:1.3.0",
                "rxlifecycle"              : "com.trello:rxlifecycle:${version["rxlifecycleSdkVersion"]}",
                "rxlifecycle-components"   : "com.trello:rxlifecycle-components:${version["rxlifecycleSdkVersion"]}",
                "rxcache"                  : "com.github.VictorAlbertos.RxCache:runtime:1.7.0-1.x",
                "rxcache-jolyglot-gson"    : "com.github.VictorAlbertos.Jolyglot:gson:0.0.3",
                "rxbinding-recyclerview-v7": "com.jakewharton.rxbinding:rxbinding-recyclerview-v7:1.0.1",
                "rxpermissions"            : "com.tbruyelle.rxpermissions:rxpermissions:0.9.4@aar",
                "rxerrorhandler"           : "me.jessyan:rxerrorhandler:1.0.1",

                //rx2
                "rxandroid2"                : "io.reactivex.rxjava2:rxandroid:2.0.1",
                "rxjava2"                   : "io.reactivex.rxjava2:rxjava:2.1.1",
                "rxlifecycle2"              : "com.trello.rxlifecycle2:rxlifecycle:${version["rxlifecycle2SdkVersion"]}",
                "rxlifecycle2-components"   : "com.trello.rxlifecycle2:rxlifecycle-components:${version["rxlifecycle2SdkVersion"]}",
                "rxcache2"                  : "com.github.VictorAlbertos.RxCache:runtime:1.8.1-2.x",
                "rxpermissions2"            : "com.tbruyelle.rxpermissions2:rxpermissions:0.9.4@aar",
                "rxerrorhandler2"           : "me.jessyan:rxerrorhandler:2.0.2",
                "rxbinding"                  :"com.jakewharton.rxbinding2:rxbinding:2.0.0",

                //tools
                "dagger2"                  : "com.google.dagger:dagger:${version["dagger2SdkVersion"]}",
                "dagger2-compiler"         : "com.google.dagger:dagger-compiler:${version["dagger2SdkVersion"]}",
                "androideventbus"          : "org.simple:androideventbus:1.0.5.1",
                "otto"                     : "com.squareup:otto:1.3.8",
                "gson"                     : "com.google.code.gson:gson:2.8.1",
                "multidex"                 : "com.android.support:multidex:1.0.1",
                "javax.annotation"         : "javax.annotation:jsr250-api:1.0",
                "arouter"                  : "com.alibaba:arouter-api:1.2.1.1",
                "arouter-compiler"         : "com.alibaba:arouter-compiler:1.1.2.1",
                "progressmanager"          : "me.jessyan:progressmanager:1.2.5",

                //test
                "junit"                    : "junit:junit:4.12",
                "androidJUnitRunner"       : "android.support.test.runner.AndroidJUnitRunner",
                "runner"                   : "com.android.support.test:runner:0.5",
                "espresso-core"            : "com.android.support.test.espresso:espresso-core:${version["espressoSdkVersion"]}",
                "espresso-contrib"         : "com.android.support.test.espresso:espresso-contrib:${version["espressoSdkVersion"]}",
                "espresso-intents"         : "com.android.support.test.espresso:espresso-intents:${version["espressoSdkVersion"]}",
                "mockito-core"             : "org.mockito:mockito-core:1.+",
                "timber"                   : "com.jakewharton.timber:timber:4.5.1",
                "logger"                   : "com.orhanobut:logger:2.1.1",
                "canary-debug"             : "com.squareup.leakcanary:leakcanary-android:${version["canarySdkVersion"]}",
                "canary-release"           : "com.squareup.leakcanary:leakcanary-android-no-op:${version["canarySdkVersion"]}",
                "umeng-analytics"          : "com.umeng.analytics:analytics:6.0.1"
        ]


}
