# Google Search Console - DNS Verification Setup

This document provides instructions for verifying domain ownership via DNS for **xponential.co.zm** with Google Search Console.

## DNS Verification Method

Add the following TXT record to your domain's DNS configuration:

```
Record Type: TXT
Name/Host: xponential.co.zm (or @)
Value: google-site-verification=RoD8zGNj0-RKC5E4xjydE_LJk-jkljim_Bjmg3WxyQA
TTL: 3600 (or default)
```

## Steps to Add the Record

### For Namecheap, GoDaddy, or similar providers:

1. Log in to your domain registrar account
2. Navigate to your domain's DNS settings
3. Add a new TXT record with:
   - **Host/Name**: `xponential.co.zm` or `@`
   - **Value**: `google-site-verification=RoD8zGNj0-RKC5E4xjydE_LJk-jkljim_Bjmg3WxyQA`
   - **TTL**: 3600 (or default)
4. Save the record
5. Return to Google Search Console and click "Verify"

## Important Notes

⚠️ **DNS Propagation**: Changes may take 15 minutes to 48 hours to propagate globally. If verification fails immediately, wait and try again.

✅ **Permanent Verification**: This method keeps your site verified as long as the TXT record remains in DNS.

✅ **No Removal Required**: Unlike the HTML file method, you can leave this record indefinitely without affecting your site.

---

**Current Status**: Meta tag ✅ | HTML file ✅ | DNS verification 📋 (instructions above)
