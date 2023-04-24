# API-funnel
Example attack: http://127.0.0.1:7331/attack?key=bootuh!841&host=https://test.com/&port=443&time=65&method=HTTPS
**GENERATE A NEW ENCRYPTION/DECRYPTION KEY IN API.PY!!**
##### Your encryption/decryption key for your logs can be found on line 17
```python
key = b'r5eHm16f-lGq3bOP8pk9Bb6XlI6t_KMju3qT7TJi6Uw=' # In the event that this key gets leaked, all your logs can be decrypted by anyone
fernet = Fernet(key)
```

**ALSO SET A NEW ADMIN KEY**
##### Your admin key for viewing key management and logs can be found in settings.yaml on line 13
```yaml
  masterkey: master1337.%!
```

## Features : 
- [x] Key management dashboard
- [x] Simple to add apis and methods
- [x] Encrypted Logs
- [x] Json bootah response
- [x] Max Attack Time
- [x] Blacklist System

- [ ] ASN Blacklist
- [ ] Range blacklist
- [ ] Concurrent System  
