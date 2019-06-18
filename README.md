# prisma_HIP-based-policy-enforcement

**Enable HIP Logs**

    Mobile_users_device_group template
        Log settings
            HIP Match
                Create "GPCS-mobile-HIP"
                Filter: "All logs"
            Check Panorama/Logging Service

**Define HIP Objects and Profiles**
    
    Mobile_users_device_group template
        HIP Objects
            Add PC: all
            Add MacOS: OSX
        HIP Profile
            Add IsPC
            Add IsMac

**Apply HIP Profiles to Security Policies**