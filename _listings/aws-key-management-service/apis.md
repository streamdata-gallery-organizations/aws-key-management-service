---
name: AWS Key Management Service
x-slug: aws-key-management-service
description: AWS Key Management Service (KMS) is a managed service that makes it easy
  for you to create and control the encryption keys used to encrypt your data, and
  uses Hardware Security Modules (HSMs) to protect the security of your keys. AWS
  Key Management Service is integrated with several other AWS services to help you
  protect the data you store with these services. AWS Key Management Service is also
  integrated with AWS CloudTrail to provide you with logs of all key usage to help
  meet your regulatory and compliance needs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Key Management Service
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Key Management Service API Cancel Key Deletion
  x-api-slug: aws-key-management-service-api
  description: Cancels the deletion of a customer master key (CMK).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=CancelKeyDeletion
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actioncancelkeydeletion-get-openapi.md
- name: AWS Key Management Service API Create Alias
  x-api-slug: aws-key-management-service-api
  description: Creates a display name for a customer master key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=CreateAlias
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actioncreatealias-get-openapi.md
- name: AWS Key Management Service API Create Grant
  x-api-slug: aws-key-management-service-api
  description: Adds a grant to a key to specify who can use the key and under what
    conditions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=CreateGrant
  tags: Grants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actioncreategrant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actioncreategrant-get-openapi.md
- name: AWS Key Management Service API Create Key
  x-api-slug: aws-key-management-service-api
  description: Creates a customer master key (CMK).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=CreateKey
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actioncreatekey-get-openapi.md
- name: AWS Key Management Service API Decrypt
  x-api-slug: aws-key-management-service-api
  description: Decrypts ciphertext.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=Decrypt
  tags: Decrypt
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiondecrypt-get-openapi.md
- name: AWS Key Management Service API Delete Alias
  x-api-slug: aws-key-management-service-api
  description: Deletes the specified alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=DeleteAlias
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiondeletealias-get-openapi.md
- name: AWS Key Management Service API Delete Imported Key Material
  x-api-slug: aws-key-management-service-api
  description: |-
    Deletes key material that you previously imported and makes the specified customer
          master key (CMK) unusable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=DeleteImportedKeyMaterial
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiondeleteimportedkeymaterial-get-openapi.md
- name: AWS Key Management Service API Describe Key
  x-api-slug: aws-key-management-service-api
  description: Provides detailed information about the specified customer master key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=DescribeKey
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiondescribekey-get-openapi.md
- name: AWS Key Management Service API Disable Key
  x-api-slug: aws-key-management-service-api
  description: |-
    Sets the state of a customer master key (CMK) to disabled, thereby preventing its use
          for cryptographic operations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=DisableKey
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiondisablekey-get-openapi.md
- name: AWS Key Management Service API Disable Key Rotation
  x-api-slug: aws-key-management-service-api
  description: Disables rotation of the specified key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=DisableKeyRotation
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiondisablekeyrotation-get-openapi.md
- name: AWS Key Management Service API Enable Key
  x-api-slug: aws-key-management-service-api
  description: Marks a key as enabled, thereby permitting its use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=EnableKey
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionenablekey-get-openapi.md
- name: AWS Key Management Service API Enable Key Rotation
  x-api-slug: aws-key-management-service-api
  description: Enables rotation of the specified customer master key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=EnableKeyRotation
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionenablekeyrotation-get-openapi.md
- name: AWS Key Management Service API Encrypt
  x-api-slug: aws-key-management-service-api
  description: Encrypts plaintext into ciphertext by using a customer master key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=Encrypt
  tags: Encrypt
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionencrypt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionencrypt-get-openapi.md
- name: AWS Key Management Service API Generate Data Key
  x-api-slug: aws-key-management-service-api
  description: |-
    Returns a data encryption key that you can use in your application to encrypt
          data locally.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=GenerateDataKey
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiongeneratedatakey-get-openapi.md
- name: AWS Key Management Service API Generate Data Key Without Plaintext
  x-api-slug: aws-key-management-service-api
  description: Returns a data encryption key encrypted under a customer master key
    (CMK).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=GenerateDataKeyWithoutPlaintext
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiongeneratedatakeywithoutplaintext-get-openapi.md
- name: AWS Key Management Service API Generate Random
  x-api-slug: aws-key-management-service-api
  description: Generates an unpredictable byte string.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=GenerateRandom
  tags: Randoms
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiongeneraterandom-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiongeneraterandom-get-openapi.md
- name: AWS Key Management Service API Get Key Policy
  x-api-slug: aws-key-management-service-api
  description: Retrieves a policy attached to the specified key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=GetKeyPolicy
  tags: Key Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiongetkeypolicy-get-openapi.md
- name: AWS Key Management Service API Get Key Rotation Status
  x-api-slug: aws-key-management-service-api
  description: |-
    Retrieves a Boolean value that indicates whether key rotation is enabled for the
          specified key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=GetKeyRotationStatus
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiongetkeyrotationstatus-get-openapi.md
- name: AWS Key Management Service API Get Parameters For Import
  x-api-slug: aws-key-management-service-api
  description: |-
    Returns the items you need in order to import key material into AWS KMS from your
          existing key management infrastructure.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=GetParametersForImport
  tags: Parameters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actiongetparametersforimport-get-openapi.md
- name: AWS Key Management Service API Import Key Material
  x-api-slug: aws-key-management-service-api
  description: |-
    Imports key material into an AWS KMS customer master key (CMK) from your existing key
          management infrastructure.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ImportKeyMaterial
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionimportkeymaterial-get-openapi.md
- name: AWS Key Management Service API List Aliases
  x-api-slug: aws-key-management-service-api
  description: Lists all of the key aliases in the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ListAliases
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionlistaliases-get-openapi.md
- name: AWS Key Management Service API List Grants
  x-api-slug: aws-key-management-service-api
  description: List the grants for a specified key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ListGrants
  tags: Grants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionlistgrants-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionlistgrants-get-openapi.md
- name: AWS Key Management Service API List Key Policies
  x-api-slug: aws-key-management-service-api
  description: Retrieves a list of policies attached to a key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ListKeyPolicies
  tags: Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionlistkeypolicies-get-openapi.md
- name: AWS Key Management Service API List Keys
  x-api-slug: aws-key-management-service-api
  description: Lists the customer master keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ListKeys
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionlistkeys-get-openapi.md
- name: AWS Key Management Service API List Retirable Grants
  x-api-slug: aws-key-management-service-api
  description: |-
    Returns a list of all grants for which the grant's RetiringPrincipal
          matches the one specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ListRetirableGrants
  tags: Grants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionlistretirablegrants-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionlistretirablegrants-get-openapi.md
- name: AWS Key Management Service API Put Key Policy
  x-api-slug: aws-key-management-service-api
  description: Attaches a key policy to the specified customer master key (CMK).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=PutKeyPolicy
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionputkeypolicy-get-openapi.md
- name: AWS Key Management Service API Re Encrypt
  x-api-slug: aws-key-management-service-api
  description: |-
    Encrypts data on the server side with a new customer master key (CMK) without exposing
          the plaintext of the data on the client side.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ReEncrypt
  tags: Encrypt
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionreencrypt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionreencrypt-get-openapi.md
- name: AWS Key Management Service API Retire Grant
  x-api-slug: aws-key-management-service-api
  description: Retires a grant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=RetireGrant
  tags: Grants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionretiregrant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionretiregrant-get-openapi.md
- name: AWS Key Management Service API Revoke Grant
  x-api-slug: aws-key-management-service-api
  description: Revokes a grant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=RevokeGrant
  tags: Grants
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionrevokegrant-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionrevokegrant-get-openapi.md
- name: AWS Key Management Service API Schedule Key Deletion
  x-api-slug: aws-key-management-service-api
  description: Schedules the deletion of a customer master key (CMK).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=ScheduleKeyDeletion
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionschedulekeydeletion-get-openapi.md
- name: AWS Key Management Service API Update Alias
  x-api-slug: aws-key-management-service-api
  description: Updates an alias to map it to a different key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=UpdateAlias
  tags: Aliases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionupdatealias-get-openapi.md
- name: AWS Key Management Service API Update Key Description
  x-api-slug: aws-key-management-service-api
  description: Updates the description of a customer master key (CMK).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: ://///?Action=UpdateKeyDescription
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/actionupdatekeydescription-get-openapi.md
- name: AWS Key Management Service API
  x-api-slug: aws-key-management-service-api
  description: AWS Key Management Service (KMS) is a managed service that makes it
    easy for you to create and control the encryption keys used to encrypt your data,
    and uses Hardware Security Modules (HSMs) to protect the security of your keys.
    AWS Key Management Service is integrated with several other AWS services to help
    you protect the data you store with these services. AWS Key Management Service
    is also integrated with AWS CloudTrail to provide you with logs of all key usage
    to help meet your regulatory and compliance needs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-key-management.jpg
  humanURL: https://aws.amazon.com/kms/
  baseURL: :///
  tags: AWS Key Management Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-key-management-service/master/_listings/aws-key-management-service/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/kms/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/kms/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/kms/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/kms/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/kms/pricing/
- type: x-website
  url: https://aws.amazon.com/kms/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---