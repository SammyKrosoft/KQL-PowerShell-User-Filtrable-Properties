# KQL filtrable properties

| **Property name** | **LDAP display name** | **Description** | **Value** |
| --- | --- | --- | --- |
| _AcceptMessagesOnlyFrom_ | _authOrig_ | _Extended attribute_ | _Extended attribute_ |
| _AcceptMessagesOnlyFromDLMembers_ | _dLMemSubmitPerms_ | _Extended attribute_ | _Extended attribute_ |
| _ActiveSyncAllowedDeviceIDs_ | _msExchMobileAllowedDeviceIds_ | _Extended attribute_ | _Extended attribute_ |
| _ActiveSyncDebugLogging_ | _msExchMobileDebugLogging_ | _Extended attribute_ | _Extended attribute_ |
| _ActiveSyncEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _ActiveSyncMailboxPolicy_ | _msExchMobileMailboxPolicyLink_ | This property contains the name of the Exchange ActiveSync mailbox policy for the mailbox. | DN |
| _AddressListMembership_ | _showInAddressBook_ | _Extended attribute_ | _Extended attribute_ |
| _Alias_ | _mailNickname_ | This property contains the alias (the generic name used to identify a mail account) of the recipient. | String / Wildcard character accepted |
| _AllowUMCallsFromNonUsers_ | _msExchUMListInDirectorySearch_ | _Extended attribute_ | _Extended attribute_ |
| _AssistantName_ | _msExchAssistantName_ | This property contains the assistant name of the recipient. | String / Wildcard character accepted |
| _C_ | _C_ | This property contains the two-letter country/region designation from International Organization for Standardization (ISO) 3166. | ISO 3166 / |
| _CallAnsweringAudioCodec_ | _msExchUMAudioCodec_ | _Extended attribute_ | _Extended attribute_ |
| _Certificate_ | _userCertificate_ | _Extended attribute_ | _Extended attribute_ |
| _City_ | _l_ | This property contains the city name of the recipient. | String / Wildcard character accepted |
| _Co_ | _Co_ | This property contains the country/region name in which the recipient resides. | Country/Region / You can locate valid Co values on the **Address and Phone** tab in the recipient's properties. |
| _CommonName_ | _cn_ | _Extended attribute_ | _Extended attribute_ |
| _Company_ | _company_ | This property contains the company of the recipient. | String / Wildcard character accepted |
| _CountryCode_ | _CountryCode_ | This property contains the numeric country/region designation from ISO 3166. | ISO 3166 / |
| _CountryOrRegion_ | Not applicable | This property contains the country or region in which the recipient resides. | Country/Region / You can locate valid CountryOrRegion values on the **Address and Phone** tab in the recipient's properties. |
| _CustomAttribute1_ | _extensionAttribute1_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute10_ | _extensionAttribute10_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute11_ | _extensionAttribute11_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute12_ | _extensionAttribute12_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute13_ | _extensionAttribute13_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute14_ | _extensionAttribute14_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute15_ | _extensionAttribute15_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute2_ | _extensionAttribute2_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute3_ | _extensionAttribute3_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute4_ | _extensionAttribute4_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute5_ | _extensionAttribute5_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute6_ | _extensionAttribute6_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute7_ | _extensionAttribute7_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute8_ | _extensionAttribute8_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _CustomAttribute9_ | _extensionAttribute9_ | This property contains a custom attribute that you can add to a recipient. | String / Wildcard character accepted |
| _Database_ | _homeMDB_ | This property contains the mailbox database. | Mailbox database / Identity / DN |
| _DeletedItemFlags_ | _deletedItemFlags_ | _Extended attribute_ | _Extended attribute_ |
| _DeliverToMailboxAndForward_ | _deliverAndRedirect_ | _Extended attribute_ | _Extended attribute_ |
| _Department_ | _department_ | This property contains the department of the recipient. | String / Wildcard character accepted |
| _Description_ | _description_ | _Extended attribute_ | _Extended attribute_ |
| _DisplayName_ | _displayName_ | This property contains the ambiguous name resolution (ANR) search for the display name of the recipient. | String / Wildcard character accepted |
| _DistinguishedName_ | _distinguishedName_ | _Extended attribute_ | _Extended attribute_ |
| _ElcExpirationSuspensionEndDate_ | _msExchELCExpirySuspensionEnd_ | _Extended attribute_ | _Extended attribute_ |
| _ElcExpirationSuspensionStartDate_ | _msExchELCExpirySuspensionStart_ | _Extended attribute_ | _Extended attribute_ |
| _ElcMailboxFlags_ | _msExchELCMailboxFlags_ | _Extended attribute_ | _Extended attribute_ |
| _EmailAddresses_ | _proxyAddresses_ | This property contains the e-mail addresses of this recipient. All Exchange 2007 e-mail address types are valid. Separate multiple values by using commas. | E-mail address / Wildcard character accepted |
| _EmailAddressPolicyEnabled_ | Not applicable | This property contains the control for applying e-mail address policies to this recipient. | Boolean / $true or $false |
| _ExchangeGuid_ | _msExchMailboxGuid_ | _Extended attribute_ | _Extended attribute_ |
| _ExchangeSecurityDescriptor_ | _msExchMailboxSecurityDescriptor_ | _Extended attribute_ | _Extended attribute_ |
| _ExchangeVersion_ | _msExchVersion_ | _Extended attribute_ | _Extended attribute_ |
| _ExpansionServer_ | _msExchExpansionServerName_ | _Extended attribute_ | _Extended attribute_ |
| _ExternalEmailAddress_ | _targetAddress_ | This property contains the external e-mail address. E-mail messages sent to the mail-enabled user are sent to this external address. | E-mail address / Wildcard character accepted |
| _ExternalOofOptions_ | _msExchExternalOOFOptions_ | This property contains the option for sending an out-of-office message to external senders. | InternalOnly / External |
| _ExternalOofOptions_ | _msExchExternalOOFOptions_ | _Extended attribute_ | _Extended attribute_ |
| _Fax_ | _facsimileTelephoneNumber_ | _Extended attribute_ | _Extended attribute_ |
| _FirstName_ | _givenName_ | This property contains the ANR search for the first name of the recipient. | String / Wildcard character accepted |
| _ForwardingAddress_ | _altRecipient_ | _Extended attribute_ | _Extended attribute_ |
| _GrantSendOnBehalfTo_ | _publicDelegates_ | _Extended attribute_ | _Extended attribute_ |
| _GroupType_ | _groupType_ | _Extended attribute_ | _Extended attribute_ |
| _Guid_ | _objectGuid_ | _Extended attribute_ | _Extended attribute_ |
| _HasActiveSyncDevicePartnership_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _HiddenFromAddressListsEnabled_ | _msExchHideFromAddressLists_ | This property specifies whether the recipient is visible in the address list. | Boolean / $true or $false |
| _HiddenGroupMembershipEnabled_ | _hideDLMembership_ | _Extended attribute_ | _Extended attribute_ |
| _HomeMTA_ | _homeMTA_ | _Extended attribute_ | _Extended attribute_ |
| _HomePhone_ | _homePhone_ | _Extended attribute_ | _Extended attribute_ |
| _Id_ | _distinguishedName_ | _Extended attribute_ | _Extended attribute_ |
| _ImapEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _IncludedRecipients_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _Initials_ | _initials_ | _Extended attribute_ | _Extended attribute_ |
| _InternetEncoding_ | _internetEncoding_ | _Extended attribute_ | _Extended attribute_ |
| _IsLinked_ | Not applicable | This property specifies whether a folder is linked to a master folder. | Boolean / $true or $false |
| _IsMailboxEnabled_ | Not applicable | This property specifies whether a mailbox is mailbox-enabled. | Boolean / $true or $false |
| _IsResource_ | Not applicable | This property specifies whether a mailbox is a resource mailbox. | Boolean / $true or $false |
| _IsShared_ | Not applicable | This property specifies whether a resource mailbox is shared. | Boolean / $true or $false |
| _IssueWarningQuota_ | _mDBStorageQuota_ | This property contains the mailbox size at which a warning message is sent to the user. | Unlimited or integer |
| _LanguagesRaw_ | _msExchUserCulture_ | This property contains the language preference for this mailbox. | [ISO 639-ISO 3166 / For example, United States English is represented as en-us. / To learn more about culture codes and for a full list of acceptable values, see CultureInfo Class in the MSDN Library.](http://go.microsoft.com/fwlink/?LinkID=67222) |
| _LastName_ | _sn_ | This property contains the ANR search for the last name of the recipient. | String / Wildcard character accepted |
| _LdapRecipientFilter_ | _msExchDynamicDLFilter_ | _Extended attribute_ | _Extended attribute_ |
| _LegacyExchangeDN_ | _legacyExchangeDN_ | _Extended attribute_ | _Extended attribute_ |
| _LinkedMasterAccount_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _LocaleID_ | _localeID_ | _Extended attribute_ | _Extended attribute_ |
| _MailboxFolderSet_ | _msExchMailboxFolderSet_ | _Extended attribute_ | _Extended attribute_ |
| _ManagedBy_ | _managedBy_ | _Extended attribute_ | _Extended attribute_ |
| _ManagedFolderMailboxPolicy_ | _msExchMailboxTemplateLink_ | This property contains the managed folder mailbox policy that controls messaging records management (MRM). | Name / GUID / DN |
| _Manager_ | _manager_ | This property contains the manager of the recipient. | String / Wildcard character accepted |
| _MAPIEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _MapiRecipient_ | _mAPIRecipient_ | _Extended attribute_ | _Extended attribute_ |
| _MasterAccountSid_ | _msExchMasterAccountSid_ | _Extended attribute_ | _Extended attribute_ |
| _MaxBlockedSenders_ | _msExchMaxBlockedSenders_ | _Extended attribute_ | _Extended attribute_ |
| _MaxReceiveSize_ | _delivContLength_ | This property contains the maximum size of messages that this recipient can receive. | Unlimited or integer |
| _MaxSafeSenders_ | _msExchMaxSafeSenders_ | _Extended attribute_ | _Extended attribute_ |
| _MaxSendSize_ | _submissionContLength_ | This property contains the maximum size of messages that this recipient can send. | Unlimited or integer |
| _MemberOfGroup_ | _memberOf_ | _Extended attribute_ | _Extended attribute_ |
| _Members_ | _member_ | _Extended attribute_ | _Extended attribute_ |
| _MessageHygieneFlags_ | _msExchMessageHygieneFlags_ | _Extended attribute_ | _Extended attribute_ |
| _MobileAdminExtendedSettings_ | _msExchOmaAdminExtendedSettings_ | _Extended attribute_ | _Extended attribute_ |
| _MobileFeaturesEnabled_ | _msExchOmaAdminWirelessEnable_ | This property specifies whether a mailbox has mobile features enabled. | Boolean / $true or $false |
| _MobileMailboxFlags_ | _msExchMobileMailboxFlags_ | _Extended attribute_ | _Extended attribute_ |
| _MobilePhone_ | _mobile_ | _Extended attribute_ | _Extended attribute_ |
| _msRTCSIP-Line_ | _msRTCSIP-Line_ | _Extended attribute_ | _Extended attribute_ |
| _Name_ | _name_ | This property contains the name of the recipient. | String |
| _Name_ | _LDAP Display Name_ | _Extended attribute_ | _Extended attribute_ |
| _Notes_ | _info_ | _Extended attribute_ | _Extended attribute_ |
| _NTSecurityDescriptor_ | _ntSecurityDescriptor_ | _Extended attribute_ | _Extended attribute_ |
| _ObjectCategory_ | _objectCategory_ | _Extended attribute_ | _Extended attribute_ |
| _ObjectClass_ | _objectClass_ | _Extended attribute_ | _Extended attribute_ |
| _ObjectState_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _Office_ | _physicalDeliveryOfficeName_ | This property contains the office of the recipient. | String |
| _OfflineAddressBook_ | _msExchUseOAB_ | This property contains the offline address book (OAB) that is associated with this recipient. | Name / GUID / DN |
| _OperatorNumber_ | _msExchUMOperatorNumber_ | _Extended attribute_ | _Extended attribute_ |
| _OriginalId_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OriginalPrimarySmtpAddress_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OriginalWindowsEmailAddress_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OtherFax_ | _otherFacsimileTelephoneNumber_ | _Extended attribute_ | _Extended attribute_ |
| _OtherHomePhone_ | _otherHomePhone_ | _Extended attribute_ | _Extended attribute_ |
| _OtherTelephone_ | _otherTelephone_ | _Extended attribute_ | _Extended attribute_ |
| _OWAActiveSyncIntegrationEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAAllAddressListsEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWACalendarEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAChangePasswordEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAContactsEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAJournalEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWANotesEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAPremiumClientEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAPublicFoldersEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWARecoverDeletedItemsEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWARemindersAndNotificationsEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWARulesEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWASearchFoldersEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWASignaturesEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWASMimeEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWASpellCheckerEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWATasksEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAThemeSelectionEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAUMIntegrationEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAUNCAccessonPrivateComputersEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAUNCAccessonPublicComputersEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAWSSAccessOnPrivateComputersEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _OWAWSSAccessOnPublicComputersEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _Pager_ | _pager_ | _Extended attribute_ | _Extended attribute_ |
| _Phone_ | _telephoneNumber_ | _Extended attribute_ | _Extended attribute_ |
| _PhoneticCompany_ | _msDS-PhoneticCompanyName_ | _Extended attribute_ | _Extended attribute_ |
| _PhoneticDepartment_ | _msDS-PhoneticDepartment_ | _Extended attribute_ | _Extended attribute_ |
| _PhoneticDisplayName_ | _msDS-PhoneticDisplayName_ | _Extended attribute_ | _Extended attribute_ |
| _PhoneticFirstName_ | _msDS-PhoneticFirstName_ | _Extended attribute_ | _Extended attribute_ |
| _PhoneticLastName_ | _msDS-PhoneticLastName_ | _Extended attribute_ | _Extended attribute_ |
| _PoliciesExcluded_ | _msExchPoliciesExcluded_ | _Extended attribute_ | _Extended attribute_ |
| _PoliciesIncluded_ | _msExchPoliciesIncluded_ | _Extended attribute_ | _Extended attribute_ |
| _PopEnabled_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _PostalCode_ | _postalCode_ | This property contains the postal code of the recipient. | String |
| _PostOfficeBox_ | _postOfficeBox_ | _Extended attribute_ | _Extended attribute_ |
| _PrimaryGroupId_ | _primaryGroupId_ | _Extended attribute_ | _Extended attribute_ |
| _PrimarySmtpAddress_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _ProhibitSendQuota_ | _mDBOverQuotaLimit_ | This property contains the mailbox size at which the user associated with this mailbox can no longer send messages. | Unlimited or integer |
| _ProhibitSendReceiveQuota_ | _mDBOverHardQuotaLimit_ | This property contains the mailbox size at which the user associated with this mailbox can no longer send or receive messages | Unlimited or integer |
| _ProtocolSettings_ | _protocolSettings_ | _Extended attribute_ | _Extended attribute_ |
| _PublicFolderContacts_ | _pFContacts_ | _Extended attribute_ | _Extended attribute_ |
| _PublicFolderRootUrl_ | _msExchPfRootUrl_ | _Extended attribute_ | _Extended attribute_ |
| _PublicFolderType_ | _msExchPFTreeType_ | _Extended attribute_ | _Extended attribute_ |
| _PurportedSearchUI_ | _msExchPurportedSearchUI_ | _Extended attribute_ | _Extended attribute_ |
| _QueryBaseDN_ | _msExchQueryBaseDN_ | _Extended attribute_ | _Extended attribute_ |
| _RawCanonicalName_ | _canonicalName_ | _Extended attribute_ | _Extended attribute_ |
| _RawExternalEmailAddress_ | _targetAddress_ | _Extended attribute_ | _Extended attribute_ |
| _RawName_ | _name_ | _Extended attribute_ | _Extended attribute_ |
| _RecipientContainer_ | _msExchDynamicDLBaseDN_ | _Extended attribute_ | _Extended attribute_ |
| _RecipientDisplayType_ | _msExchRecipientDisplayType_ | _Extended attribute_ | _Extended attribute_ |
| _RecipientFilter_ | _msExchQueryFilter_ | _Extended attribute_ | _Extended attribute_ |
| _RecipientLimits_ | _msExchRecipLimit_ | This property contains the maximum number of recipients per message to which this mailbox can send. | Unlimited or integer |
| _RecipientType_ | Not applicable | This property specifies the recipient type. | UserMailbox / MailUser / MailContact / MailUniversalDistributionGroup / MailUniversalSecurityGroup / MailNonUniversalGroup / DynamicDistributionGroup / PublicFolder |
| _RecipientTypeDetails_ | Not applicable | This property specifies the recipient subtype. | ConferenceRoomMailbox / EquipmentMailbox / LegacyMailbox / LinkedMailbox / UserMailbox / MailContact / DynamicDistributionGroup / MailForestContact / MailNonUniversalGroup / MailUniversalDistributionGroup / MailUniversalSecurityGroup / MailUser / PublicFolder / SharedMailbox |
| _RejectMessagesFrom_ | _unauthOrig_ | _Extended attribute_ | _Extended attribute_ |
| _RejectMessagesFromDLMembers_ | _dLMemRejectPerms_ | _Extended attribute_ | _Extended attribute_ |
| _ReportToManagerEnabled_ | _reportToOwner_ | _Extended attribute_ | _Extended attribute_ |
| _ReportToOriginatorEnabled_ | _reportToOriginator_ | _Extended attribute_ | _Extended attribute_ |
| _RequireAllSendersAreAuthenticated_ | _msExchRequireAuthToSendTo_ | _Extended attribute_ | _Extended attribute_ |
| _ResourceCapacity_ | _msExchResourceCapacity_ | _Extended attribute_ | _Extended attribute_ |
| _ResourceCustom_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _ResourceMetaData_ | _msExchResourceMetaData_ | _Extended attribute_ | _Extended attribute_ |
| _ResourcePropertiesDisplay_ | _msExchResourceDisplay_ | _Extended attribute_ | _Extended attribute_ |
| _ResourceSearchProperties_ | _msExchResourceSearchProperties_ | _Extended attribute_ | _Extended attribute_ |
| _ResourceType_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _RetainDeletedItemsFor_ | _garbageCollPeriod_ | _Extended attribute_ | _Extended attribute_ |
| _RTCSIPPrimaryUserAddress_ | _msRTCSIP-PrimaryUserAddress_ | _Extended attribute_ | _Extended attribute_ |
| _RulesQuota_ | _msExchMDBRulesQuota_ | _Extended attribute_ | _Extended attribute_ |
| _SafeRecipientsHash_ | _msExchSafeRecipientsHash_ | _Extended attribute_ | _Extended attribute_ |
| _SafeSendersHash_ | _msExchSafeSendersHash_ | _Extended attribute_ | _Extended attribute_ |
| _SamAccountName_ | _SamAccountName_ | This property contains the logon name that is used to support client computers and servers running older versions of the operating system, such as Microsoft Windows NT 4.0, Windows 98, Windows 95, and LAN Manager. | String / Wildcard character accepted |
| _SCLDeleteThresholdInt_ | _msExchMessageHygieneSCLDeleteThreshold_ | _Extended attribute_ | _Extended attribute_ |
| _SCLJunkThresholdInt_ | _msExchMessageHygieneSCLJunkThreshold_ | _Extended attribute_ | _Extended attribute_ |
| _SCLQuarantineThresholdInt_ | _msExchMessageHygieneSCLQuarantineThreshold_ | _Extended attribute_ | _Extended attribute_ |
| _SCLRejectThresholdInt_ | _msExchMessageHygieneSCLRejectThreshold_ | _Extended attribute_ | _Extended attribute_ |
| _SecurityProtocol_ | _securityProtocol_ | _Extended attribute_ | _Extended attribute_ |
| _SendDeliveryReportsTo_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _SendOofMessageToOriginatorEnabled_ | _oOFReplyToOriginator_ | _Extended attribute_ | _Extended attribute_ |
| _ServerLegacyDN_ | _msExchHomeServerName_ | _Extended attribute_ | _Extended attribute_ |
| _ServerName_ | Not applicable | This property contains the name of the server where the recipient resides. | Server name |
| _Sid_ | _objectSid_ | _Extended attribute_ | _Extended attribute_ |
| _SidHistory_ | _sIDHistory_ | _Extended attribute_ | _Extended attribute_ |
| _SimpleDisplayName_ | _displayNamePrintable_ | _Extended attribute_ | _Extended attribute_ |
| _SMimeCertificate_ | _userSMIMECertificate_ | _Extended attribute_ | _Extended attribute_ |
| _StateOrProvince_ | _st_ | This property contains the state or province information that is defined for this recipient. | String / Wildcard character accepted |
| _StreetAddress_ | _streetAddress_ | This property contains the street address that is defined for this recipient. | String |
| _TelephoneAssistant_ | _telephoneAssistant_ | _Extended attribute_ | _Extended attribute_ |
| _TextEncodedORAddress_ | _textEncodedORAddress_ | _Extended attribute_ | _Extended attribute_ |
| _Title_ | _title_ | This property contains the title of the recipient. | String |
| _UMDtmfMap_ | _msExchUMDtmfMap_ | _Extended attribute_ | _Extended attribute_ |
| _UMEnabled_ | Not applicable | This property specifies whether Unified Messaging (UM) is enabled for this mailbox. | Boolean / $true or $false |
| _UMEnabledFlags_ | _msExchUMEnabledFlags_ | _Extended attribute_ | _Extended attribute_ |
| _UMMailboxPolicy_ | _msExchUMTemplateLink_ | _Extended attribute_ | _Extended attribute_ |
| _UMPinChecksum_ | _msExchUMPinChecksum_ | _Extended attribute_ | _Extended attribute_ |
| _UMRecipientDialPlanId_ | _msExchUMRecipientDialPlanLink_ | _Extended attribute_ | _Extended attribute_ |
| _UMServerWritableFlags_ | _msExchUMServerWritableFlags_ | _Extended attribute_ | _Extended attribute_ |
| _UMSpokenName_ | _msExchUMSpokenName_ | _Extended attribute_ | _Extended attribute_ |
| _UnicodePassword_ | _unicodePwd_ | _Extended attribute_ | _Extended attribute_ |
| _UseDatabaseQuotaDefaults_ | _mDBUseDefaults_ | This property specifies whether the mailbox uses the quota attributes for the mailbox database in which this mailbox resides. The quota attributes are: ProhibitSendQuota, ProhibitSendReceiveQuota, IssueWarningQuota, and RulesQuota. | ProhibitSendQuota / ProhibitSendReceiveQuota / IssueWarningQuota / RulesQuota |
| _UserAccountControl_ | _userAccountControl_ | _Extended attribute_ | _Extended attribute_ |
| _UserPrincipalName_ | _userPrincipalName_ | This property contains the user principal name (UPN) for this recipient. The UPN is the logon name for the user and consists of a user name and a suffix. Typically, the suffix is the domain name where the user account resides. For example, kim@contoso.com. | User logon name / User principal name / Wildcard character accepted |
| _ViewDepth_ | _Not applicable_ | _Extended attribute_ | _Extended attribute_ |
| _WebPage_ | _wWWHomePage_ | _Extended attribute_ | _Extended attribute_ |

