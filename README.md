- 👋 Hi, I’m @RajparaAkash


- ⚡ Useful Code

- AppCompatDelegate.setDefaultNightMode(AppCompatDelegate.MODE_NIGHT_NO);
- android:excludeFromRecents="true"

- android.useAndroidX=true
- android.nonTransitiveRClass=true
- android.nonFinalResIds=false
- android.enableJetifier=true
- android.defaults.buildfeatures.buildconfig=true

- android:foreground="?android:attr/selectableItemBackground"
- defaultConfig {
        resConfigs "en", "ar", "de", "es", "fr", "hi", "in", "it", "ja", "ko", "nl", "pt", "ru", "sv", "zh",
                "bn", "fa", "gu", "ha", "jv", "mr", "pa","pl", "sw", "ta", "te", "th", "tr", "ur", "vi"
    }

  bundle {
        language {
            enableSplit = false
        }
    }

- buildFeatures {
        buildConfig = true
        viewBinding = true
    }

- MediaScannerConnection.scanFile(VaultGridDataActivity.this,new String[]{new File(folderPath).getAbsolutePath()}, null, null);

- File file = new File(context.getExternalFilesDir(null), ".TEMP");
- getFilesDir()
- getExternalFilesDir(null)

- overridePendingTransition(0, 0);
  
- jniLibs
  ndk.abiFilters 'arm64-v8a','armeabi-v7a','x86','x86_64'


- <com.google.android.material.imageview.ShapeableImageView
        android:id="@+id/imageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:adjustViewBounds="true"
        android:background="#F3F3F3"
        app:shapeAppearanceOverlay="@style/RoundedCorner3dp" />

  <style name="RoundedCorner3dp">
        <item name="cornerSize">3%</item>
    </style>

- getOnBackPressedDispatcher().onBackPressed();

- getOnBackPressedDispatcher().addCallback(new OnBackPressedCallback(true) {
            @Override
            public void handleOnBackPressed() {
                finish();
            }
        });

- private void configureBackPressedBehavior() {
        OnBackPressedCallback callback = new OnBackPressedCallback(true) {
            @Override
            public void handleOnBackPressed() {
                finish();
            }
        };
        getOnBackPressedDispatcher().addCallback(this, callback);

        binding.backLay.setOnClickListener(view -> {
            callback.handleOnBackPressed();
        });
    }

- runOnUiThread(() -> {
                    
                });

- android:extractNativeLibs="false"
- android:hardwareAccelerated="true"
- android:largeHeap="true"
- android:networkSecurityConfig="@xml/network_security_config"
- android:requestLegacyExternalStorage="true"
- android:usesCleartextTraffic="true"

- ExecutorService

- buildConfigField "String", "APP_BASE_URL", "\"https://admaker.postai.in/\""

  
