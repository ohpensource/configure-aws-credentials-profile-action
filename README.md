# configure-aws-credentials-profile-action

* Action configures aws credentials and creates profile.

```yaml
      - uses: ohpensource/configure-aws-credentials-profile-action@v1.0.0
        name: Configure AWS credentials
        with:
          aws-profile-name: dev
          role-to-assume: <<role_arn>>          

      - uses: ohpensource/configure-aws-credentials-profile-action@v1.0.0
        name: Configure AWS credentials
        with:
          aws-profile-name: dev
          role-to-assume: <<role_arn>>
          aws-source-profile: <<source_profile_name>>
```

# License Summary

This code is made available under the MIT license. Details [here](LICENSE).

