Galaxy pass finger sdk: http://developer.samsung.com/galaxy/pass

Samsung s5 with Android 6.0

Android native api
```
mFingerprintManager.isHardwareDetected() is false;
mFingerprintManager.hasEnrolledFingerprints() is false
```

```
/**
    * Determine if fingerprint hardware is present and functional.
    *
    * @return true if hardware is present and functional, false otherwise.
    */
mFingerprintManager.isHardwareDetected() is false;

   /**
    * Determine if there is at least one fingerprint enrolled.
    *
    * @return true if at least one fingerprint is enrolled, false otherwise
    */
mFingerprintManager.hasEnrolledFingerprints() is false
```

Samsung support self finger sdk.

this is the demo.