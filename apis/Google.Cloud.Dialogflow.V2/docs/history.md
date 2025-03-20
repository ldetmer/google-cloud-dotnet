# Version history

## Version 1.3.0-beta01, released 2025-03-20

Release Google.Cloud.Dialogflow.V2 version 4.26.0 (#14417)


Changes in this release:

### New features

- Add new RPC IngestContextReferences, GenerateSuggestions ([commit 449b11f](https://togithub.com/googleapis/google-cloud-dotnet/commit/449b11fdbf523e78cecdb8d1798393aab03c1c50))
- Added support for TelephonyConnectionInfo, country_code and ControlPoint ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Added support for CONVERSATION_SUMMARIZATION ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Added ConversatioalTrainingAssignments, ConversationalTrainingMembers, ConversationalTrainingModules,ConversationalTrainingTeams API ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Added support for audio_input and speech_model ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Changed enablle_partial_automated_agent_reply to optional ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))

### Documentation improvements

- Clarified wording around phrase_sets ([commit 449b11f](https://togithub.com/googleapis/google-cloud-dotnet/commit/449b11fdbf523e78cecdb8d1798393aab03c1c50))
- Clarified wording around filter and document_correctness ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Clarified wording around use_timeout_based_endpointing ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Changed reference link around ConversationStage ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Clarified wording around boost_specs and filter_specs ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Clarified wording around send_time ([commit 57d2148](https://togithub.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))

feat: Add new RPC IngestContextReferences, GenerateSuggestions
docs: clarified wording around phrase_sets

PiperOrigin-RevId: 733912069

Source-Link: https://github.com/googleapis/googleapis/commit/c57048e5e01822cbac85d8d16660cd096454d00f

Source-Link: https://github.com/googleapis/googleapis-gen/commit/d295b21090cd90d0b2f895d5269f718b1f9fbee8
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZDI5NWIyMTA5MGNkOTBkMGIyZjg5NWQ1MjY5ZjcxOGIxZjlmYmVlOCJ9

feat: added support for TelephonyConnectionInfo, country_code and ControlPoint
feat: added support for CONVERSATION_SUMMARIZATION
feat: added ConversatioalTrainingAssignments, ConversationalTrainingMembers, ConversationalTrainingModules,ConversationalTrainingTeams API
feat: added support for audio_input and speech_model
feat: changed enablle_partial_automated_agent_reply to optional
docs: clarified wording around filter and document_correctness
docs: clarified wording around use_timeout_based_endpointing
docs: changed reference link around ConversationStage
docs: clarified wording around boost_specs and filter_specs
docs: clarified wording around send_time

PiperOrigin-RevId: 733074841

Source-Link: https://github.com/googleapis/googleapis/commit/cd8473077feb6d521a959ab650e31530a51526bf

Source-Link: https://github.com/googleapis/googleapis-gen/commit/19922e065289ccb7a7756d52ac6b09ca8e597284
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMTk5MjJlMDY1Mjg5Y2NiN2E3NzU2ZDUyYWM2YjA5Y2E4ZTU5NzI4NCJ9

chore: update copyright year for auto-generated protos

PiperOrigin-RevId: 732130682

Source-Link: https://github.com/googleapis/googleapis/commit/9415ba048aa587b1b2df2b96fc00aa009c831597

Source-Link: https://github.com/googleapis/googleapis-gen/commit/2905f833756c2b20b3282be84b511e040fe54f33
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlndGFibGUuVjIvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2hhbm5lbC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2xvdWRCdWlsZC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2xvdWRCdWlsZC5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2xvdWRRdW90YXMuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2xvdWRRdW90YXMuVjFCZXRhLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ29uZmlkZW50aWFsQ29tcHV0aW5nLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ29uZmlkZW50aWFsQ29tcHV0aW5nLlYxQWxwaGExLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ29uZmlnLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ29udGFpbmVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUNhdGFsb2cuTGluZWFnZS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUZ1c2lvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YWZsb3cuVjFCZXRhMy8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXByb2MuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0b3JlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGV2VG9vbHMuQ29udGFpbmVyQW5hbHlzaXMuVjEvLk93bEJvdC55YW1sIiwiaCI6IjI5MDVmODMzNzU2YzJiMjBiMzI4MmJlODRiNTExZTA0MGZlNTRmMzMifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGV2ZWxvcGVyQ29ubmVjdC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5DeC5WMy8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMjkwNWY4MzM3NTZjMmIyMGIzMjgyYmU4NGI1MTFlMDQwZmU1NGYzMyJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMkJldGExLy5Pd2xCb3QueWFtbCIsImgiOiIyOTA1ZjgzMzc1NmMyYjIwYjMyODJiZTg0YjUxMWUwNDBmZTU0ZjMzIn0=

chore: Regenerate all APIs to update copyright year

Release Google.Cloud.Dialogflow.V2 version 4.25.0

Changes in this release:

### New features

- Add new fields for delivering intermediate transcriptions through PubSub ([commit b94ea2a](https://github.com/googleapis/google-cloud-dotnet/commit/b94ea2a6f6ca0d2551c7471c018da65ee381f65c))

feat: add new fields for delivering intermediate transcriptions through PubSub

PiperOrigin-RevId: 705999588

Source-Link: https://github.com/googleapis/googleapis/commit/35c27e3dff6a232c9c83014c677cf353c3a8aaf5

Source-Link: https://github.com/googleapis/googleapis-gen/commit/fb8444ee2d1364e2e6a84e112206e886e003b8e6
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZmI4NDQ0ZWUyZDEzNjRlMmU2YTg0ZTExMjIwNmU4ODZlMDAzYjhlNiJ9

Release Google.Cloud.Dialogflow.V2 version 4.24.0 (#13944)


Changes in this release:

### New features

- Properly mark TrainingPhrase name field output-only ([commit d336935](https://togithub.com/googleapis/google-cloud-dotnet/commit/d336935d53910959377f0437f88cee1f1577ebf9))

### Documentation improvements

- Fixed the references to proto method / fields ([commit d336935](https://togithub.com/googleapis/google-cloud-dotnet/commit/d336935d53910959377f0437f88cee1f1577ebf9))

chore: Regenerate all project files

This is basically removing the version override for GAX, gRPC etc.

feat: properly mark TrainingPhrase name field output-only
docs: fixed the references to proto method / fields

PiperOrigin-RevId: 702736565

Source-Link: https://github.com/googleapis/googleapis/commit/6989f679896e2318b02d7e6c74b6d65aa2290824

Source-Link: https://github.com/googleapis/googleapis-gen/commit/50364718af0486eaa5c2fa2925414be858d0cf7d
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNTAzNjQ3MThhZjA0ODZlYWE1YzJmYTI5MjU0MTRiZTg1OGQwY2Y3ZCJ9

Release Google.Cloud.Dialogflow.V2 version 4.23.0 (#13839)


Changes in this release:

### New features

- Add options of query_source, search_config, end_user_metadata and exact_search ([commit a08e4da](https://togithub.com/googleapis/google-cloud-dotnet/commit/a08e4da2ff37af2a1097ff51e91c694f4b445515))
- Expose metadata in AnswerSource ([commit a08e4da](https://togithub.com/googleapis/google-cloud-dotnet/commit/a08e4da2ff37af2a1097ff51e91c694f4b445515))
- Added support for ALAW encoding ([commit b206f21](https://togithub.com/googleapis/google-cloud-dotnet/commit/b206f2191e4dcf31df81e2d540ab4ed3bc5c8fb7))
- Add options of query_source, search_config and context_size ([commit b206f21](https://togithub.com/googleapis/google-cloud-dotnet/commit/b206f2191e4dcf31df81e2d540ab4ed3bc5c8fb7))

feat: add options of query_source, search_config, end_user_metadata and exact_search
feat: expose metadata in AnswerSource

PiperOrigin-RevId: 695456323

Source-Link: https://github.com/googleapis/googleapis/commit/8081c741a09ca02c4bc7082b025dad9653f4d317

Source-Link: https://github.com/googleapis/googleapis-gen/commit/a74e716b2345a869d25c2feadf20c9a43b1cf469
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiYTc0ZTcxNmIyMzQ1YTg2OWQyNWMyZmVhZGYyMGM5YTQzYjFjZjQ2OSJ9

feat: added support for ALAW encoding
feat: add options of query_source, search_config and context_size

PiperOrigin-RevId: 693786098

Source-Link: https://github.com/googleapis/googleapis/commit/35214c2b09a6d4d124c143046b688a4dcf2215a9

Source-Link: https://github.com/googleapis/googleapis-gen/commit/d6b4c370af40ca9b3e030b15f4642562083cb90f
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZDZiNGMzNzBhZjQwY2E5YjNlMDMwYjE1ZjQ2NDI1NjIwODNjYjkwZiJ9

Release Google.Cloud.Dialogflow.V2 version 4.22.0 (#13603)


Changes in this release:

### New features

- Created new boolean fields in conversation dataset for zone isolation and zone separation compliance status ([commit 1a9f58d](https://togithub.com/googleapis/google-cloud-dotnet/commit/1a9f58dd2cf7690fc50ec780c2f573ccda43eccb))
- Add ALAW encoding value to Audio encoding enum ([commit 1a9f58d](https://togithub.com/googleapis/google-cloud-dotnet/commit/1a9f58dd2cf7690fc50ec780c2f573ccda43eccb))
- Created new boolean fields in conversation model for zone isolation and zone separation compliance status ([commit 24e7f8f](https://togithub.com/googleapis/google-cloud-dotnet/commit/24e7f8f17a28c721b9eae24260db021a42292583))

chore: Regenerate all project files with updated dependencies

feat: created new boolean fields in conversation dataset for zone isolation and zone separation compliance status
feat: add ALAW encoding value to Audio encoding enum

PiperOrigin-RevId: 678636701

Source-Link: https://github.com/googleapis/googleapis/commit/0ede901c455762b9d55ea3cf386f50663d0650ba

Source-Link: https://github.com/googleapis/googleapis-gen/commit/39c42782febc92124134995b2e7d78be762bcc22
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMzljNDI3ODJmZWJjOTIxMjQxMzQ5OTViMmU3ZDc4YmU3NjJiY2MyMiJ9

feat: created new boolean fields in conversation model for zone isolation and zone separation compliance status

PiperOrigin-RevId: 676665642

Source-Link: https://github.com/googleapis/googleapis/commit/f87ae4487b303f32c3ddc9638649d32dda2e2776

Source-Link: https://github.com/googleapis/googleapis-gen/commit/d66ac41aa072bbc4367f7d2758d0d0ba7a7094a5
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZDY2YWM0MWFhMDcyYmJjNDM2N2Y3ZDI3NThkMGQwYmE3YTcwOTRhNSJ9

chore: Regenerate all (generated) project files

Release Google.Cloud.Dialogflow.V2 version 4.21.0 (#13368)


Changes in this release:

### Bug fixes

- Changed field behavior for an existing field `parent` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- Changed field behavior for an existing field `session_id` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))

### New features

- Add Proactive Generative Knowledge Assist endpoints and types ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- Add Generator related services and types ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- Add GenerateStatelessSuggestion related endpoints and types ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))

### Documentation improvements

- A comment for field `name` in message `.google.cloud.dialogflow.v2.Conversation` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `conversation_stage` in message `.google.cloud.dialogflow.v2.Conversation` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `filter` in message `.google.cloud.dialogflow.v2.ListConversationsRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `context_size` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `assist_query_params` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.GenerateStatelessSummaryRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `max_context_size` in message `.google.cloud.dialogflow.v2.GenerateStatelessSummaryRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `parent` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `session_id` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `conversation` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for message `HumanAgentHandoffConfig` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `live_person_config` in message `.google.cloud.dialogflow.v2.HumanAgentHandoffConfig` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `audio` in message `.google.cloud.dialogflow.v2.AudioInput` is changed ([commit b56beb4](https://togithub.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))

feat: Add Proactive Generative Knowledge Assist endpoints and types
feat: Add Generator related services and types
feat: Add GenerateStatelessSuggestion related endpoints and types
docs: A comment for field `name` in message `.google.cloud.dialogflow.v2.Conversation` is changed
docs: A comment for field `conversation_stage` in message `.google.cloud.dialogflow.v2.Conversation` is changed
docs: A comment for field `filter` in message `.google.cloud.dialogflow.v2.ListConversationsRequest` is changed
docs: A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed
docs: A comment for field `context_size` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed
docs: A comment for field `assist_query_params` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed
docs: A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.GenerateStatelessSummaryRequest` is changed
docs: A comment for field `max_context_size` in message `.google.cloud.dialogflow.v2.GenerateStatelessSummaryRequest` is changed
docs: A comment for field `parent` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed
docs: A comment for field `session_id` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed
docs: A comment for field `conversation` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed
docs: A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed
docs: A comment for message `HumanAgentHandoffConfig` is changed
docs: A comment for field `live_person_config` in message `.google.cloud.dialogflow.v2.HumanAgentHandoffConfig` is changed
docs: A comment for field `audio` in message `.google.cloud.dialogflow.v2.AudioInput` is changed
fix: Changed field behavior for an existing field `parent` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest`
fix: Changed field behavior for an existing field `session_id` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest`

PiperOrigin-RevId: 658854047

Source-Link: https://github.com/googleapis/googleapis/commit/dcbd1d4b2cbc19e6ce2226ed706b0dbbfba48788

Source-Link: https://github.com/googleapis/googleapis-gen/commit/feac4cf807f0ab41bd59878af46eb4fd2ece5679
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZmVhYzRjZjgwN2YwYWI0MWJkNTk4NzhhZjQ2ZWI0ZmQyZWNlNTY3OSJ9

chore: Regenerate all APIs with generator v1.4.32

Release Google.Cloud.Dialogflow.V2 version 4.20.0 (#13106)


Changes in this release:

### New features

- Add properties for nested resource name references ([commit 15eec4d](https://togithub.com/googleapis/google-cloud-dotnet/commit/15eec4dabb9fd3cf3b8f4b978d64b7ba435ca995))

feat: Add properties for nested resource name references

chore: Regenerate with sorted using alias directives

(This should generate no semantic diffs between old and new code.)

Release Google.Cloud.Dialogflow.V2 version 4.19.0 (#12848)


Changes in this release:

### New features

- Add IServiceCollection extension methods for client registration where an IServiceProvider is required. ([commit 022fab2](https://togithub.com/googleapis/google-cloud-dotnet/commit/022fab203f28fb9c608972af7f8b83f571ae5694))

chore: update copyright year for auto-generated protos

PiperOrigin-RevId: 631538781

Source-Link: https://github.com/googleapis/googleapis/commit/3597f7db2191c00b100400991ef96e52d62f5841

Source-Link: https://github.com/googleapis/googleapis-gen/commit/8021fdf8d66f6005519c044d5834124b677dc919
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUNhdGFsb2cuVjEvLk93bEJvdC55YW1sIiwiaCI6IjgwMjFmZGY4ZDY2ZjYwMDU1MTljMDQ0ZDU4MzQxMjRiNjc3ZGM5MTkifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUZ1c2lvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiODAyMWZkZjhkNjZmNjAwNTUxOWMwNDRkNTgzNDEyNGI2NzdkYzkxOSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUxhYmVsaW5nLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6IjgwMjFmZGY4ZDY2ZjYwMDU1MTljMDQ0ZDU4MzQxMjRiNjc3ZGM5MTkifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YWZvcm0uVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiODAyMWZkZjhkNjZmNjAwNTUxOWMwNDRkNTgzNDEyNGI2NzdkYzkxOSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXBsZXguVjEvLk93bEJvdC55YW1sIiwiaCI6IjgwMjFmZGY4ZDY2ZjYwMDU1MTljMDQ0ZDU4MzQxMjRiNjc3ZGM5MTkifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXByb2MuVjEvLk93bEJvdC55YW1sIiwiaCI6IjgwMjFmZGY4ZDY2ZjYwMDU1MTljMDQ0ZDU4MzQxMjRiNjc3ZGM5MTkifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0cmVhbS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiODAyMWZkZjhkNjZmNjAwNTUxOWMwNDRkNTgzNDEyNGI2NzdkYzkxOSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0cmVhbS5WMUFscGhhMS8uT3dsQm90LnlhbWwiLCJoIjoiODAyMWZkZjhkNjZmNjAwNTUxOWMwNDRkNTgzNDEyNGI2NzdkYzkxOSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGVwbG95LlYxLy5Pd2xCb3QueWFtbCIsImgiOiI4MDIxZmRmOGQ2NmY2MDA1NTE5YzA0NGQ1ODM0MTI0YjY3N2RjOTE5In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5DeC5WMy8uT3dsQm90LnlhbWwiLCJoIjoiODAyMWZkZjhkNjZmNjAwNTUxOWMwNDRkNTgzNDEyNGI2NzdkYzkxOSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiODAyMWZkZjhkNjZmNjAwNTUxOWMwNDRkNTgzNDEyNGI2NzdkYzkxOSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMkJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI4MDIxZmRmOGQ2NmY2MDA1NTE5YzA0NGQ1ODM0MTI0YjY3N2RjOTE5In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZUNvbnRyb2wuVjEvLk93bEJvdC55YW1sIiwiaCI6IjgwMjFmZGY4ZDY2ZjYwMDU1MTljMDQ0ZDU4MzQxMjRiNjc3ZGM5MTkifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZU1hbmFnZW1lbnQuVjEvLk93bEJvdC55YW1sIiwiaCI6IjgwMjFmZGY4ZDY2ZjYwMDU1MTljMDQ0ZDU4MzQxMjRiNjc3ZGM5MTkifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZVVzYWdlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI4MDIxZmRmOGQ2NmY2MDA1NTE5YzA0NGQ1ODM0MTI0YjY3N2RjOTE5In0=

chore: Regenerate all APIs with new generator

This adds IServiceCollection extension methods for client registration where an IServiceProvider is required.

Release Google.Cloud.Dialogflow.V2 version 4.18.0 (#12325)


Changes in this release:

### New features

- Change netstandard2.1 target to netstandard2.0 ([commit 82bea85](https://togithub.com/googleapis/google-cloud-dotnet/commit/82bea850661975b9750ac30753528cc9d2e05240))

feat: Change netstandard2.1 target to netstandard2.0

This allows libraries targeting netstandard2.0 to depend on this library.

Release Google.Cloud.Dialogflow.V2 version 4.17.0 (#12202)


Changes in this release:

### New features

- Added text sections to the submitted summary ([commit 720a6ad](https://togithub.com/googleapis/google-cloud-dotnet/commit/720a6ad8a0c11a7a7d386208b22f04c1afa48769))
- Added conformer model migration opt out flag ([commit 720a6ad](https://togithub.com/googleapis/google-cloud-dotnet/commit/720a6ad8a0c11a7a7d386208b22f04c1afa48769))

### Documentation improvements

- Clarified wording around END_OF_SINGLE_UTTERANCE ([commit 720a6ad](https://togithub.com/googleapis/google-cloud-dotnet/commit/720a6ad8a0c11a7a7d386208b22f04c1afa48769))

chore: Regenerate all clients with the new generator

The only change is how the ClientHelper is constructed.

This excludes:

- Google.Cloud.Storage.V2 which has broader changes
- Google.Cloud.PubSub.V1 which currently targets GAX 4.7.0

chore: Regenerate project files

chore: Regenerate all projects

feat: added text sections to the submitted summary
feat: added conformer model migration opt out flag
docs: clarified wording around END_OF_SINGLE_UTTERANCE

PiperOrigin-RevId: 614805668

Source-Link: https://github.com/googleapis/googleapis/commit/14d09ef74340c67d6adffaea5483b0226f62dcc6

Source-Link: https://github.com/googleapis/googleapis-gen/commit/e60ad0b5cd964482218af0810802f8bfa2ec64d2
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZTYwYWQwYjVjZDk2NDQ4MjIxOGFmMDgxMDgwMmY4YmZhMmVjNjRkMiJ9

Release Google.Cloud.Dialogflow.V2 version 4.16.0 (#11880)


Changes in this release:

No API surface changes; just dependency updates.

chore: Update dependencies in all APIs

chore: set packed = false on field_behavior extension

PiperOrigin-RevId: 604675854

Source-Link: https://github.com/googleapis/googleapis/commit/42c04fea4338ba626095ec2cde5ea75827191581

Source-Link: https://github.com/googleapis/googleapis-gen/commit/a1ed8a97a00d02fe456f6ebd4160c5b2b000ad75
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ29udGFpbmVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiJhMWVkOGE5N2EwMGQwMmZlNDU2ZjZlYmQ0MTYwYzViMmIwMDBhZDc1In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUNhdGFsb2cuTGluZWFnZS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUNhdGFsb2cuVjEvLk93bEJvdC55YW1sIiwiaCI6ImExZWQ4YTk3YTAwZDAyZmU0NTZmNmViZDQxNjBjNWIyYjAwMGFkNzUifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUZ1c2lvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUxhYmVsaW5nLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6ImExZWQ4YTk3YTAwZDAyZmU0NTZmNmViZDQxNjBjNWIyYjAwMGFkNzUifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YWZsb3cuVjFCZXRhMy8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YWZvcm0uVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXBsZXguVjEvLk93bEJvdC55YW1sIiwiaCI6ImExZWQ4YTk3YTAwZDAyZmU0NTZmNmViZDQxNjBjNWIyYjAwMGFkNzUifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXByb2MuVjEvLk93bEJvdC55YW1sIiwiaCI6ImExZWQ4YTk3YTAwZDAyZmU0NTZmNmViZDQxNjBjNWIyYjAwMGFkNzUifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0b3JlLkFkbWluLlYxLy5Pd2xCb3QueWFtbCIsImgiOiJhMWVkOGE5N2EwMGQwMmZlNDU2ZjZlYmQ0MTYwYzViMmIwMDBhZDc1In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0b3JlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiJhMWVkOGE5N2EwMGQwMmZlNDU2ZjZlYmQ0MTYwYzViMmIwMDBhZDc1In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0cmVhbS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0cmVhbS5WMUFscGhhMS8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGVwbG95LlYxLy5Pd2xCb3QueWFtbCIsImgiOiJhMWVkOGE5N2EwMGQwMmZlNDU2ZjZlYmQ0MTYwYzViMmIwMDBhZDc1In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGV2VG9vbHMuQ29udGFpbmVyQW5hbHlzaXMuVjEvLk93bEJvdC55YW1sIiwiaCI6ImExZWQ4YTk3YTAwZDAyZmU0NTZmNmViZDQxNjBjNWIyYjAwMGFkNzUifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5DeC5WMy8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMkJldGExLy5Pd2xCb3QueWFtbCIsImgiOiJhMWVkOGE5N2EwMGQwMmZlNDU2ZjZlYmQ0MTYwYzViMmIwMDBhZDc1In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlzY292ZXJ5RW5naW5lLlYxLy5Pd2xCb3QueWFtbCIsImgiOiJhMWVkOGE5N2EwMGQwMmZlNDU2ZjZlYmQ0MTYwYzViMmIwMDBhZDc1In0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlzY292ZXJ5RW5naW5lLlYxQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiYTFlZDhhOTdhMDBkMDJmZTQ1NmY2ZWJkNDE2MGM1YjJiMDAwYWQ3NSJ9

chore: Regenerate all APIs (#11597)

(Using the new GAPIC generator, new protoc generator and new gRPC generator.)

AIPlatform v1 has been reverted, as it doesn't currently build.
chore: Update dependencies for all libraries.

So that we don't have to manually update GAX to get the newest common protos.

Release Google.Cloud.Dialogflow.V2 version 4.15.0 (#11497)


Changes in this release:

### New features

- Add sections field to HumanAgentAssistantConfig.SuggestionQueryConfig ([commit 9dcd3d1](https://togithub.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))
- Add enable_conversation_augmented_query field to HumanAgentAssistantConfig.SuggestionFeatureConfig message ([commit 9dcd3d1](https://togithub.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))
- Add INTENT enum in SearchKnowledgeAnswer.AnswerType message ([commit 9dcd3d1](https://togithub.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))
- Add rewritten_query in field in SearchKnowledgeResponse message ([commit 9dcd3d1](https://togithub.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))

### Documentation improvements

- Improved comments on audio_config proto ([commit 9dcd3d1](https://togithub.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))

chore: Batch API regeneration for copyright lines

This change will make OwlBot-authored changes smaller. In the future
we may want to work out a way of avoiding updating copyright years
at all.

There are a few APIs that are out of date or don't generate for one
reason or another; I'll deal with those separately.

feat: add sections field to HumanAgentAssistantConfig.SuggestionQueryConfig
feat: add enable_conversation_augmented_query field to HumanAgentAssistantConfig.SuggestionFeatureConfig message
feat: add INTENT enum in SearchKnowledgeAnswer.AnswerType message
feat: add rewritten_query in field in SearchKnowledgeResponse message
docs: improved comments on audio_config proto

PiperOrigin-RevId: 591055870

Source-Link: https://github.com/googleapis/googleapis/commit/2f93f44f05133aae3281e338dcc9887eeb04008a

Source-Link: https://github.com/googleapis/googleapis-gen/commit/2154bfc0d50dba0b8b8980e80243d928c9977108
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMjE1NGJmYzBkNTBkYmEwYjhiODk4MGU4MDI0M2Q5MjhjOTk3NzEwOCJ9

Release Google.Cloud.Dialogflow.V2 version 4.14.0 (#11124)


Changes in this release:

### New features

- Add the enable_extended_streaming flag ([commit 7db6a56](https://togithub.com/googleapis/google-cloud-dotnet/commit/7db6a5666de3ea07b6321f28e5df8dc42db2097d))

feat: Add the enable_partial_automated_agent_reply flag
chore: remove extraneous backend config

PiperOrigin-RevId: 569315665

Source-Link: https://github.com/googleapis/googleapis/commit/a24bc5647ff31502afee5439e0dee9b3bc632cc4

Source-Link: https://github.com/googleapis/googleapis-gen/commit/afd064365f9a266b32950068054b3c2c5da374bd
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiYWZkMDY0MzY1ZjlhMjY2YjMyOTUwMDY4MDU0YjNjMmM1ZGEzNzRiZCJ9

Release Google.Cloud.Dialogflow.V2 version 4.13.0 (#10997)


Changes in this release:

### New features

- Added speech endpointing setting ([commit b08f369](https://togithub.com/googleapis/google-cloud-dotnet/commit/b08f369651e6a6877f9527f3b5c881bc34f1ead9))
- Added Knowledge Search API ([commit b08f369](https://togithub.com/googleapis/google-cloud-dotnet/commit/b08f369651e6a6877f9527f3b5c881bc34f1ead9))

feat: added speech endpointing setting
feat: added Knowledge Search API

PiperOrigin-RevId: 560215389

Source-Link: https://github.com/googleapis/googleapis/commit/b1666e6f4fe427dd942e0afe9f5177acd954fadb

Source-Link: https://github.com/googleapis/googleapis-gen/commit/07e82b4d4917494d85039722f673d409c4c7305f
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMDdlODJiNGQ0OTE3NDk0ZDg1MDM5NzIyZjY3M2Q0MDljNGM3MzA1ZiJ9

Release Google.Cloud.Dialogflow.V2 version 4.12.0 (#10878)


Changes in this release:

### New features

- Added baseline model version used to generate the summary ([commit 561a1e0](https://togithub.com/googleapis/google-cloud-dotnet/commit/561a1e0215af68aa92c4ff57a1b863e8f8dde700))
- Added the platform of the virtual agent response messages ([commit 561a1e0](https://togithub.com/googleapis/google-cloud-dotnet/commit/561a1e0215af68aa92c4ff57a1b863e8f8dde700))

### Documentation improvements

- Minor formatting ([commit 388c3e2](https://togithub.com/googleapis/google-cloud-dotnet/commit/388c3e2e054dc58062aa1ea7b24c5e613456defc))
- Minor formatting ([commit 7648d13](https://togithub.com/googleapis/google-cloud-dotnet/commit/7648d133650b0ae986da702d4948dcef308221bb))
- Added google.api.field_behavior for some fields in audio_config ([commit 8588148](https://togithub.com/googleapis/google-cloud-dotnet/commit/858814847ba8e5b7f6ca123cc8f806db2742d375))

feat: added baseline model version used to generate the summary
feat: added the platform of the virtual agent response messages

PiperOrigin-RevId: 555788605

Source-Link: https://github.com/googleapis/googleapis/commit/90a551c2a02613507a2f0f05fd25d133113a1a1c

Source-Link: https://github.com/googleapis/googleapis-gen/commit/30620b4f34713860083fff036982900b1004cbf5
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMzA2MjBiNGYzNDcxMzg2MDA4M2ZmZjAzNjk4MjkwMGIxMDA0Y2JmNSJ9

docs: Minor formatting

PiperOrigin-RevId: 553461544

Source-Link: https://github.com/googleapis/googleapis/commit/347e81de5db1ac895f36d99cb0af7dfbb8d5bdab

Source-Link: https://github.com/googleapis/googleapis-gen/commit/1177b663de50079dbcfcbb7eebe99c7ee21ca074
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMTE3N2I2NjNkZTUwMDc5ZGJjZmNiYjdlZWJlOTljN2VlMjFjYTA3NCJ9

docs: Minor formatting

PiperOrigin-RevId: 552837489

Source-Link: https://github.com/googleapis/googleapis/commit/7154a947675ffa9b846e1a899dbc90bc79598352

Source-Link: https://github.com/googleapis/googleapis-gen/commit/4538a83a0a087c3b1cc09245f0ed86875eb8832d
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNDUzOGE4M2EwYTA4N2MzYjFjYzA5MjQ1ZjBlZDg2ODc1ZWI4ODMyZCJ9

docs: added google.api.field_behavior for some fields in audio_config

PiperOrigin-RevId: 546447860

Source-Link: https://github.com/googleapis/googleapis/commit/52535ce4b70f393f03aef789432127afca998e1e

Source-Link: https://github.com/googleapis/googleapis-gen/commit/14c79ff7cc28037a9922d7e22131ebcb587e1166
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMTRjNzlmZjdjYzI4MDM3YTk5MjJkN2UyMjEzMWViY2I1ODdlMTE2NiJ9

Release Google.Cloud.Dialogflow.V2 version 4.11.0 (#10591)


Changes in this release:

### New features

- Added dialogflow_assist_answer ([commit 4d022ec](https://togithub.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added session_ttl ([commit 4d022ec](https://togithub.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added human_agent_side_config ([commit 4d022ec](https://togithub.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added suggestion_input ([commit 4d022ec](https://togithub.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added suggest_dialogflow_assists_response ([commit 4d022ec](https://togithub.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added suggest_entity_extraction_response ([commit 4d022ec](https://togithub.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))

feat: added dialogflow_assist_answer
feat: added session_ttl
feat: added human_agent_side_config
feat: added suggestion_input
feat: added suggest_dialogflow_assists_response
feat: added suggest_entity_extraction_response

PiperOrigin-RevId: 542021587

Source-Link: https://github.com/googleapis/googleapis/commit/f40416dd8e0b3c6ef0d696cf772b04ce153fc5f5

Source-Link: https://github.com/googleapis/googleapis-gen/commit/04ca491dec8f35173ee599d7ed07936b4086e96d
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMDRjYTQ5MWRlYzhmMzUxNzNlZTU5OWQ3ZWQwNzkzNmI0MDg2ZTk2ZCJ9

chore: Regenerate all APIs with newer protoc/gRPC plugins

chore: Update dependencies for all APIs

This will allow us to update the generator to use protoc 3.23.x.
It does mean that we can't release *patch* versions of libraries without either undoing these changes or creating a branch - but that's unlikely to cause an issue.

Release Google.Cloud.Dialogflow.V2 version 4.10.0 (#10336)


Changes in this release:

### New features

- Add baseline model configuration for conversation summarization ([commit fe578a7](https://togithub.com/googleapis/google-cloud-dotnet/commit/fe578a7cbccdebc73b5c3dae63efd9be68a38298))
- Extended StreamingListCallCompanionEvents timeout to 600 seconds ([commit ddd7f08](https://togithub.com/googleapis/google-cloud-dotnet/commit/ddd7f0877f1fb600eb42a5e169525a37b6dd99c0))
- Added debug info for StreamingDetectIntent ([commit ddd7f08](https://togithub.com/googleapis/google-cloud-dotnet/commit/ddd7f0877f1fb600eb42a5e169525a37b6dd99c0))
- Added GenerateStatelessSummary method ([commit ddd7f08](https://togithub.com/googleapis/google-cloud-dotnet/commit/ddd7f0877f1fb600eb42a5e169525a37b6dd99c0))

feat: add baseline model configuration for conversation summarization

PiperOrigin-RevId: 530749453

Source-Link: https://github.com/googleapis/googleapis/commit/620a0237207496cefd53296f3528c65be14f0571

Source-Link: https://github.com/googleapis/googleapis-gen/commit/300d63819c2a27ecd7f35edf88051b44ab291828
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMzAwZDYzODE5YzJhMjdlY2Q3ZjM1ZWRmODgwNTFiNDRhYjI5MTgyOCJ9

feat: extended StreamingListCallCompanionEvents timeout to 600 seconds
feat: added debug info for StreamingDetectIntent
feat: added GenerateStatelessSummary method

PiperOrigin-RevId: 530102437

Source-Link: https://github.com/googleapis/googleapis/commit/cea4ed9b7871b1a2eb85b7593ccf0f5269df08b2

Source-Link: https://github.com/googleapis/googleapis-gen/commit/624b26c099fb2c601741d774015502bef99e1bea
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNjI0YjI2YzA5OWZiMmM2MDE3NDFkNzc0MDE1NTAyYmVmOTllMWJlYSJ9

Release Google.Cloud.Dialogflow.V2 version 4.9.0 (#9994)


Changes in this release:

### New features

- Added support for custom content types ([commit 15d6a43](https://togithub.com/googleapis/google-cloud-dotnet/commit/15d6a439b9d0c204c1b60751848318ccd69f3358))

### Documentation improvements

- Clarified wording around quota usage ([commit 15d6a43](https://togithub.com/googleapis/google-cloud-dotnet/commit/15d6a439b9d0c204c1b60751848318ccd69f3358))

feat: added support for custom content types
docs: clarified wording around quota usage

PiperOrigin-RevId: 513681148

Source-Link: https://github.com/googleapis/googleapis/commit/3b8869b89a700b57d3054136c45532abbdb884cf

Source-Link: https://github.com/googleapis/googleapis-gen/commit/c1c7570b315ff2cc965c17a3c9a834b2af18ae0c
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiYzFjNzU3MGIzMTVmZjJjYzk2NWMxN2EzYzlhODM0YjJhZjE4YWUwYyJ9

Release Google.Cloud.Dialogflow.V2 version 4.8.0 (#9934)


Changes in this release:

### New features

- Added support for AssistQueryParameters and SynthesizeSpeechConfig ([commit 22e5419](https://togithub.com/googleapis/google-cloud-dotnet/commit/22e5419cf66c7db39753a3c17588fa5324eb7bfe))

### Documentation improvements

- Add more meaningful comments ([commit 22e5419](https://togithub.com/googleapis/google-cloud-dotnet/commit/22e5419cf66c7db39753a3c17588fa5324eb7bfe))

feat: added support for AssistQueryParameters and SynthesizeSpeechConfig
docs: add more meaningful comments

PiperOrigin-RevId: 510042252

Source-Link: https://github.com/googleapis/googleapis/commit/7b30db729561f4f426eedab20f2a54e54e87b4b5

Source-Link: https://github.com/googleapis/googleapis-gen/commit/17beb9941750b31faa423a29d7a018346a6b88b5
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMTdiZWI5OTQxNzUwYjMxZmFhNDIzYTI5ZDdhMDE4MzQ2YTZiODhiNSJ9

Release Google.Cloud.Dialogflow.V2 version 4.7.0 (#9682)


Changes in this release:

### New features

- Enable REST transport in C# ([commit 496c8ab](https://togithub.com/googleapis/google-cloud-dotnet/commit/496c8abe53e80646e5dd5a6d4a2231b11b36969a))

feat(csharp): Enable REST transport in C#

This change does not affect other languages.

PiperOrigin-RevId: 503088494

Source-Link: https://github.com/googleapis/googleapis/commit/fcff1cc4120d8ffdc0cdef23a7939dc7ba467065

Source-Link: https://github.com/googleapis/googleapis-gen/commit/3f6f05ee81a3a16066ee6aa6626c1555cce2a8bf
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQW5hbHl0aWNzLkFkbWluLlYxQWxwaGEvLk93bEJvdC55YW1sIiwiaCI6IjNmNmYwNWVlODFhM2ExNjA2NmVlNmFhNjYyNmMxNTU1Y2NlMmE4YmYifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQW5hbHl0aWNzLkFkbWluLlYxQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQW5hbHl0aWNzLkRhdGEuVjFCZXRhLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXBpR2F0ZXdheS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXBpZ2VlQ29ubmVjdC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXNzdXJlZFdvcmtsb2Fkcy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXNzdXJlZFdvcmtsb2Fkcy5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXV0b01MLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmFyZU1ldGFsU29sdXRpb24uVjIvLk93bEJvdC55YW1sIiwiaCI6IjNmNmYwNWVlODFhM2ExNjA2NmVlNmFhNjYyNmMxNTU1Y2NlMmE4YmYifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmluYXJ5QXV0aG9yaXphdGlvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmluYXJ5QXV0aG9yaXphdGlvbi5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2hhbm5lbC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGVwbG95LlYxLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRG9tYWlucy5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRXZlbnRhcmMuVjEvLk93bEJvdC55YW1sIiwiaCI6IjNmNmYwNWVlODFhM2ExNjA2NmVlNmFhNjYyNmMxNTU1Y2NlMmE4YmYifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRnVuY3Rpb25zLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRnVuY3Rpb25zLlYyLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRnVuY3Rpb25zLlYyQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiM2Y2ZjA1ZWU4MWEzYTE2MDY2ZWU2YWE2NjI2YzE1NTVjY2UyYThiZiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuR2tlQmFja3VwLlYxLy5Pd2xCb3QueWFtbCIsImgiOiIzZjZmMDVlZTgxYTNhMTYwNjZlZTZhYTY2MjZjMTU1NWNjZTJhOGJmIn0=

Release Google.Cloud.Dialogflow.V2 version 4.6.0 (#9580)


Changes in this release:

### New features

- Added SuggestConversationSummary RPC ([commit 833acec](https://togithub.com/googleapis/google-cloud-dotnet/commit/833acec549980676e804fab02b422be55ddcbc5f))

### Documentation improvements

- Updated go library package ([commit 833acec](https://togithub.com/googleapis/google-cloud-dotnet/commit/833acec549980676e804fab02b422be55ddcbc5f))

feat: Added SuggestConversationSummary RPC
docs: updated go library package

PiperOrigin-RevId: 501862436

Source-Link: https://github.com/googleapis/googleapis/commit/155e0f4123ba003055587768944a47498c48926b

Source-Link: https://github.com/googleapis/googleapis-gen/commit/3051f617a991c274c88d27064e803095e4ef9d39
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMzA1MWY2MTdhOTkxYzI3NGM4OGQyNzA2NGU4MDMwOTVlNGVmOWQzOSJ9

chore: Update copyright notices

chore: Enable requesting numeric enums in "transport=rest" responses for services supporting this (Java, Go, Python, PHP, TypeScript, C#, and Ruby), even if they do not yet turn on REST transport

chore: disallow "transport=rest" for services where numeric enums are not confirmed to be supported (except in PHP and Java)
PiperOrigin-RevId: 493113566

Source-Link: https://github.com/googleapis/googleapis/commit/758f0d1217d9c7fe398aa5efb1057ce4b6409e55

Source-Link: https://github.com/googleapis/googleapis-gen/commit/78bd8f05e1276363eb14eae70e91fe4bc20703ab
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQW5hbHl0aWNzLkFkbWluLlYxQWxwaGEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQW5hbHl0aWNzLkFkbWluLlYxQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQW5hbHl0aWNzLkRhdGEuVjFCZXRhLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQXJlYTEyMC5UYWJsZXMuVjFBbHBoYTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQWNjZXNzQXBwcm92YWwuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXBpR2F0ZXdheS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXBpZ2VlQ29ubmVjdC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXBpZ2VlUmVnaXN0cnkuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXBpS2V5cy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXBwRW5naW5lLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXJ0aWZhY3RSZWdpc3RyeS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXJ0aWZhY3RSZWdpc3RyeS5WMUJldGEyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXNzZXQuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXNzdXJlZFdvcmtsb2Fkcy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXNzdXJlZFdvcmtsb2Fkcy5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQXV0b01MLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmFyZU1ldGFsU29sdXRpb24uVjIvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmF0Y2guVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmF0Y2guVjFBbHBoYS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmV5b25kQ29ycC5BcHBDb25uZWN0aW9ucy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmV5b25kQ29ycC5BcHBDb25uZWN0b3JzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmV5b25kQ29ycC5BcHBHYXRld2F5cy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmV5b25kQ29ycC5DbGllbnRDb25uZWN0b3JTZXJ2aWNlcy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmV5b25kQ29ycC5DbGllbnRHYXRld2F5cy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlnUXVlcnkuQ29ubmVjdGlvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlnUXVlcnkuRGF0YVRyYW5zZmVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlnUXVlcnkuUmVzZXJ2YXRpb24uVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlndGFibGUuQWRtaW4uVjIvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlndGFibGUuVjIvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlsbGluZy5CdWRnZXRzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlsbGluZy5CdWRnZXRzLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmlsbGluZy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmluYXJ5QXV0aG9yaXphdGlvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQmluYXJ5QXV0aG9yaXphdGlvbi5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2VydGlmaWNhdGVNYW5hZ2VyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2hhbm5lbC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2xvdWRCdWlsZC5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ2xvdWREbXMuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ29udGFjdENlbnRlckluc2lnaHRzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuQ29udGFpbmVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YWZsb3cuVjFCZXRhMy8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YWZvcm0uVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUZ1c2lvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YUxhYmVsaW5nLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXBsZXguVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXByb2MuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0b3JlLkFkbWluLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0b3JlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0cmVhbS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGF0YXN0cmVhbS5WMUFscGhhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGVidWdnZXIuVjIvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGVwbG95LlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGV2VG9vbHMuQ29udGFpbmVyQW5hbHlzaXMuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5DeC5WMy8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlzY292ZXJ5RW5naW5lLlYxQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGxwLlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRG9jdW1lbnRBSS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRG9jdW1lbnRBSS5WMUJldGEzLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRG9tYWlucy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRG9tYWlucy5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRW50ZXJwcmlzZUtub3dsZWRnZUdyYXBoLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRXJyb3JSZXBvcnRpbmcuVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRXNzZW50aWFsQ29udGFjdHMuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRXZlbnRhcmMuUHVibGlzaGluZy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRXZlbnRhcmMuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRmlsZXN0b3JlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRmlyZXN0b3JlLkFkbWluLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRmlyZXN0b3JlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRnVuY3Rpb25zLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRnVuY3Rpb25zLlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRnVuY3Rpb25zLlYyQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuR2FtaW5nLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuR2FtaW5nLlYxQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuR2tlQmFja3VwLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuR2tlSHViLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuR2tlSHViLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuR1N1aXRlQWRkT25zLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuSWFtLkFkbWluLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuSWFtLkNyZWRlbnRpYWxzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuSWFtLlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuSWFwLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuSWRzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuSW90LlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuS21zLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTGFuZ3VhZ2UuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTGlmZVNjaWVuY2VzLlYyQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTG9jYXRpb24vLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTG9nZ2luZy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTWFuYWdlZElkZW50aXRpZXMuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTWVkaWFUcmFuc2xhdGlvbi5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTWVtY2FjaGUuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTWVtY2FjaGUuVjFCZXRhMi8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTWV0YXN0b3JlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTWV0YXN0b3JlLlYxQWxwaGEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTW9uaXRvcmluZy5WMy8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTmV0d29ya0Nvbm5lY3Rpdml0eS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTmV0d29ya0Nvbm5lY3Rpdml0eS5WMUFscGhhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTmV0d29ya01hbmFnZW1lbnQuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTmV0d29ya1NlY3VyaXR5LlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTm90ZWJvb2tzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuTm90ZWJvb2tzLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuT3B0aW1pemF0aW9uLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuT3JjaGVzdHJhdGlvbi5BaXJmbG93LlNlcnZpY2UuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuT3JnUG9saWN5LlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuT3NDb25maWcuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuT3NDb25maWcuVjFBbHBoYS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuT3NMb2dpbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuT3NMb2dpbi5WMUJldGEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUGhpc2hpbmdQcm90ZWN0aW9uLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUG9saWN5VHJvdWJsZXNob290ZXIuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUHJpdmF0ZUNhdGFsb2cuVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUHJvZmlsZXIuVjIvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUHViU3ViLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVjYXB0Y2hhRW50ZXJwcmlzZS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVjYXB0Y2hhRW50ZXJwcmlzZS5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVjb21tZW5kYXRpb25FbmdpbmUuVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVjb21tZW5kZXIuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVkaXMuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVkaXMuVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVzb3VyY2VNYW5hZ2VyLlYzLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmVzb3VyY2VTZXR0aW5ncy5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUmV0YWlsLlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuUnVuLlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2NoZWR1bGVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VjcmV0TWFuYWdlci5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VjcmV0TWFuYWdlci5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VjdXJpdHkuUHJpdmF0ZUNBLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VjdXJpdHkuUHJpdmF0ZUNBLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VjdXJpdHkuUHVibGljQ0EuVjFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VjdXJpdHlDZW50ZXIuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VjdXJpdHlDZW50ZXIuVjFQMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZUNvbnRyb2wuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZURpcmVjdG9yeS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZURpcmVjdG9yeS5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZU1hbmFnZW1lbnQuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2VydmljZVVzYWdlLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU2hlbGwuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU3Bhbm5lci5BZG1pbi5EYXRhYmFzZS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU3Bhbm5lci5BZG1pbi5JbnN0YW5jZS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU3Bhbm5lci5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU3BlZWNoLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU3BlZWNoLlYxUDFCZXRhMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU3BlZWNoLlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuU3RvcmFnZVRyYW5zZmVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVGFsZW50LlY0Ly5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVGFsZW50LlY0QmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVGFza3MuVjIvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVGFza3MuVjJCZXRhMy8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVGV4dFRvU3BlZWNoLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVGV4dFRvU3BlZWNoLlYxQmV0YTEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVHB1LlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVHJhY2UuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVHJhY2UuVjIvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVHJhbnNsYXRlLlYzLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlkZW8uTGl2ZVN0cmVhbS5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlkZW8uU3RpdGNoZXIuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlkZW8uVHJhbnNjb2Rlci5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlkZW9JbnRlbGxpZ2VuY2UuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVmlzaW9uLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVk1NaWdyYXRpb24uVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuVnBjQWNjZXNzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV2ViUmlzay5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV2ViUmlzay5WMUJldGExLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV2ViU2VjdXJpdHlTY2FubmVyLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya2Zsb3dzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuV29ya2Zsb3dzLlYxQmV0YS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuSWRlbnRpdHkuQWNjZXNzQ29udGV4dE1hbmFnZXIuVjEvLk93bEJvdC55YW1sIiwiaCI6Ijc4YmQ4ZjA1ZTEyNzYzNjNlYjE0ZWFlNzBlOTFmZTRiYzIwNzAzYWIifQ==
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuTWFwcy5BZGRyZXNzVmFsaWRhdGlvbi5WMS8uT3dsQm90LnlhbWwiLCJoIjoiNzhiZDhmMDVlMTI3NjM2M2ViMTRlYWU3MGU5MWZlNGJjMjA3MDNhYiJ9
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuTWFwcy5Sb3V0aW5nLlYyLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=
Copy-Tag: eyJwIjoiYXBpcy9HcmFmZWFzLlYxLy5Pd2xCb3QueWFtbCIsImgiOiI3OGJkOGYwNWUxMjc2MzYzZWIxNGVhZTcwZTkxZmU0YmMyMDcwM2FiIn0=

Release Google.Cloud.Dialogflow.V2 version 4.5.0 (#9382)


Changes in this release:

### New features

- Added cx_current_page field to AutomatedAgentReply ([commit 2e15dd1](https://togithub.com/googleapis/google-cloud-dotnet/commit/2e15dd164b6552055ea6c9f2ba23f8b9e75959f3))

### Documentation improvements

- Clarified docs for Sentiment ([commit 2e15dd1](https://togithub.com/googleapis/google-cloud-dotnet/commit/2e15dd164b6552055ea6c9f2ba23f8b9e75959f3))

feat: added cx_current_page field to AutomatedAgentReply
docs: clarified docs for Sentiment

PiperOrigin-RevId: 490103678

Source-Link: https://github.com/googleapis/googleapis/commit/8f95a5f2d5032f040d93874bf8e63b33d135d11d

Source-Link: https://github.com/googleapis/googleapis-gen/commit/fed1c108dbe9291c14f7f305ca1e8bf2830c9c60
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZmVkMWMxMDhkYmU5MjkxYzE0ZjdmMzA1Y2ExZThiZjI4MzBjOWM2MCJ9

chore: Regenerate all APIs

chore: Regenerate projects with GAX 4.2.0

Release Google.Cloud.Dialogflow.V2 version 4.4.0 (#9263)


Changes in this release:

### New features

- Added StreamingAnalyzeContent API ([commit bdfcd9e](https://togithub.com/googleapis/google-cloud-dotnet/commit/bdfcd9e76fbd1ff7e47bd590bdf073749a088568))
- Added obfuscated_external_user_id to Participant ([commit bdfcd9e](https://togithub.com/googleapis/google-cloud-dotnet/commit/bdfcd9e76fbd1ff7e47bd590bdf073749a088568))
- Can directly set Cloud Speech model on the SpeechToTextConfig ([commit bdfcd9e](https://togithub.com/googleapis/google-cloud-dotnet/commit/bdfcd9e76fbd1ff7e47bd590bdf073749a088568))

feat: Added StreamingAnalyzeContent API
feat: Added obfuscated_external_user_id to Participant
feat: Can directly set Cloud Speech model on the SpeechToTextConfig

PiperOrigin-RevId: 483696090

Source-Link: https://github.com/googleapis/googleapis/commit/3772bf3656425cb32ed3525894f8b1a2a5dfa789

Source-Link: https://github.com/googleapis/googleapis-gen/commit/e358d269b1f0eb9964189d18768823bc9e8ab41c
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZTM1OGQyNjliMWYwZWI5OTY0MTg5ZDE4NzY4ODIzYmM5ZThhYjQxYyJ9

Release Google.Cloud.Dialogflow.V2 version 4.3.0 (#9226)


Changes in this release:

### New features

- Include conversation dataset name to be created with dataset creation metadata ([commit 293e1ff](https://togithub.com/googleapis/google-cloud-dotnet/commit/293e1ff997ea8ccedf5812dda0392089cfbe8228))

### Documentation improvements

- Clarify SuggestionFeature enums which are specific to chat agents ([commit 293e1ff](https://togithub.com/googleapis/google-cloud-dotnet/commit/293e1ff997ea8ccedf5812dda0392089cfbe8228))

feat: include conversation dataset name to be created with dataset creation metadata
docs: clarify SuggestionFeature enums which are specific to chat agents

PiperOrigin-RevId: 478522249

Source-Link: https://github.com/googleapis/googleapis/commit/8bd89cd4fc964360198362ef49c72ef90543bf45

Source-Link: https://github.com/googleapis/googleapis-gen/commit/ddf381e8fcebbdde902df0419b30908d01c63e0e
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZGRmMzgxZThmY2ViYmRkZTkwMmRmMDQxOWIzMDkwOGQwMWM2M2UwZSJ9

Release Google.Cloud.Dialogflow.V2 version 4.2.0 (#9127)


Changes in this release:

### Documentation improvements

- Added an explicit note that DetectIntentRequest's text input is limited by 256 characters ([commit 0fd3a71](https://github.com/googleapis/google-cloud-dotnet/commit/0fd3a71d2b6bead1e2fb0e0761add19f4785d2ee))

chore: Regenerate Google.Cloud.Dialogflow.V2

chore: Regenerate all APIs with the new generator

The only changes should be due to XML escaping

Release Google.Cloud.Dialogflow.V2Beta1 version 1.0.0-beta01 (#9059)


Changes in this release:

Initial release.

chore: Regenerate all APIs with gRPC tools 2.47.0

Only changes are an additional warning being suppressed, and a redundant space in doc comments being removed.

Update generator to v1.4.4 (#8929)


docs: added an explicit note that DetectIntentRequest's text input is limited by 256 characters

PiperOrigin-RevId: 463252698

Source-Link: https://github.com/googleapis/googleapis/commit/eeacaabc368d70217b086f66c2c1644b105f337c

Source-Link: https://github.com/googleapis/googleapis-gen/commit/da3bfa08ba77d14ba66e6eeee5ad159ef365df0f
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZGEzYmZhMDhiYTc3ZDE0YmE2NmU2ZWVlZTVhZDE1OWVmMzY1ZGYwZiJ9

chore: Regenerate all APIs

chore: regenerate all APIs

This only affects ordering for PackageApiMetadata and DI extension methods.
(At some point we may want to make that ordering explicit and canonical, but I believe it's already actually stable when build configs don't change.)

Release Google.Cloud.Dialogflow.V2 version 4.1.0 (#8861)


Changes in this release:

### New features

- Deprecated the filter field and add resource_definition ([commit 05d7b7b](https://github.com/googleapis/google-cloud-dotnet/commit/05d7b7b5e149a6bcf813db29a787b77902b28326))

### Documentation improvements

- Add more meaningful comments ([commit 05d7b7b](https://github.com/googleapis/google-cloud-dotnet/commit/05d7b7b5e149a6bcf813db29a787b77902b28326))

chore: Add Google.Cloud.Location dependency to Google.Cloud.Dialogflow.V2

feat: deprecated the filter field and add resource_definition
docs: add more meaningful comments

PiperOrigin-RevId: 458520697

Source-Link: https://github.com/googleapis/googleapis/commit/2bf9d8d49e07e77cb06ea2e50589eb3e76b013f1

Source-Link: https://github.com/googleapis/googleapis-gen/commit/ce2a70aadab1593d6daf8609e5fdd0cf0c644bbc
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiY2UyYTcwYWFkYWIxNTkzZDZkYWY4NjA5ZTVmZGQwY2YwYzY0NGJiYyJ9

chore: Regenerate project files

Release Google.Cloud.Dialogflow.V2 version 4.0.0 (#8655)


Changes in this release:

This is the first version of this package to depend on GAX v4.

There are some breaking changes, both in GAX v4 and in the generated code. The changes that aren't specific to any given API are [described in the Google Cloud documentation](https://cloud.google.com/dotnet/docs/reference/help/breaking-gax4). We don't anticipate any changes to most customer code, but please [file a GitHub issue](https://github.com/googleapis/google-cloud-dotnet/issues/new/choose) if you run into problems.

The most important change in this release is the use of the Grpc.Net.Client package for gRPC communication, instead of Grpc.Core. When using .NET Core 3.1 or .NET 5.0+ this should lead to a smaller installation footprint and greater compatibility (e.g. with Apple M1 chips). Any significant change in a core component comes with the risk of incompatibility, however - so again, please let us know if you encounter any issues.

### API-specific Breaking changes

- Correct broken ConversationModelEvaluation resource pattern ([commit 52734a8](https://github.com/googleapis/google-cloud-dotnet/commit/52734a83d8a941fc01978bffe260ea60bbbd27fb))

### Documentation improvements

- Add the fields for setting CX virtual agent session parameters ([commit f697491](https://github.com/googleapis/google-cloud-dotnet/commit/f69749149a6c84e32e18a50aacbc3b7ad838774f))
- Added explanation for SuggestionResult ([commit 15b7174](https://github.com/googleapis/google-cloud-dotnet/commit/15b717491e9a3458e4b396e472a3503e49acf150))

chore: Regenerate projects

chore: Regenerate project files

chore: Regenerate project files

chore: Regenerate all projects

chore: Regenerate projects

chore: Regenerate all APIs

chore: Regenerate project files

chore: Remove obsolete client constructors accepting a Channel

chore: Regenerate all project files

docs: add the fields for setting CX virtual agent session parameters

PiperOrigin-RevId: 446825520

Source-Link: https://github.com/googleapis/googleapis/commit/f6bb25583b9b7320c9642a28fde9101b492da930

Source-Link: https://github.com/googleapis/googleapis-gen/commit/cd1450b403b5a3f92676d8a34f0cfc07fc767b40
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiY2QxNDUwYjQwM2I1YTNmOTI2NzZkOGEzNGYwY2ZjMDdmYzc2N2I0MCJ9

fix!: correct broken ConversationModelEvaluation resource pattern

PiperOrigin-RevId: 442646533

Source-Link: https://github.com/googleapis/googleapis/commit/b62c5624bd0e6d84af879f8cea7b5862efb2a131

Source-Link: https://github.com/googleapis/googleapis-gen/commit/f5c157c68115847d78eb8412734cb82e7d5515b4
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZjVjMTU3YzY4MTE1ODQ3ZDc4ZWI4NDEyNzM0Y2I4MmU3ZDU1MTViNCJ9

docs: added explanation for SuggestionResult

PiperOrigin-RevId: 435670355

Source-Link: https://github.com/googleapis/googleapis/commit/5d85995dbd61d6a0b331f93e6244876cdd366e8c

Source-Link: https://github.com/googleapis/googleapis-gen/commit/1b913e4484a66b3f4d01c55be174704272466264
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMWI5MTNlNDQ4NGE2NmIzZjRkMDFjNTViZTE3NDcwNDI3MjQ2NjI2NCJ9

Release Google.Cloud.Dialogflow.V2 version 3.11.0 (#8243)


Changes in this release:

### New features

- Added ConversationModel resource and its APIs ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added ConversationDataset resource and its APIs ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added SetSuggestionFeatureConfig and ClearSuggestionFeatureConfig APIs for ConversationProfile ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added new knowledge type of Document content ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added states of Document ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added metadata for the Knowledge operation ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))

### Documentation improvements

- Clarified the behavior of language_code in EventInput in the context of a followup event input ([commit 3449846](https://github.com/googleapis/google-cloud-dotnet/commit/3449846a23e7806e98db432bfcb00f52eee8b838))
- Clarified wording around Cloud Storage usage ([commit 3449846](https://github.com/googleapis/google-cloud-dotnet/commit/3449846a23e7806e98db432bfcb00f52eee8b838))
- Added a new resource name pattern for ConversationModel ([commit 3449846](https://github.com/googleapis/google-cloud-dotnet/commit/3449846a23e7806e98db432bfcb00f52eee8b838))

docs: clarified the behavior of language_code in EventInput in the context of a followup event input
docs: clarified wording around Cloud Storage usage
docs: added a new resource name pattern for ConversationModel

PiperOrigin-RevId: 432962774

Source-Link: https://github.com/googleapis/googleapis/commit/5556688216b2884d540da675c23d88d42cb856b3

Source-Link: https://github.com/googleapis/googleapis-gen/commit/ca6f30a2233469ff7da361fe9fb78784dcbc6c7e
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiY2E2ZjMwYTIyMzM0NjlmZjdkYTM2MWZlOWZiNzg3ODRkY2JjNmM3ZSJ9

feat: added ConversationModel resource and its APIs
feat: added ConversationDataset resource and its APIs
feat: added SetSuggestionFeatureConfig and ClearSuggestionFeatureConfig APIs for ConversationProfile
feat: added new knowledge type of Document content
feat: added states of Document
feat: added metadata for the Knowledge operation
docs: updated copyright

PiperOrigin-RevId: 430829291

Source-Link: https://github.com/googleapis/googleapis/commit/83795ddb9586420bbd6732f9a80d9546a9f91dcd

Source-Link: https://github.com/googleapis/googleapis-gen/commit/b6b58a4d9b2cd6657bb6d6406c901f16d1d5213f
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiYjZiNThhNGQ5YjJjZDY2NTdiYjZkNjQwNmM5MDFmMTZkMWQ1MjEzZiJ9

chore: Regenerate project files

Release Google.Cloud.Dialogflow.V2 version 3.10.0 (#7930)


Changes in this release:

### New features

- Added conversation process config, ImportDocument and SuggestSmartReplies API ([commit 7d25d83](https://github.com/googleapis/google-cloud-dotnet/commit/7d25d8374eee6a36251e1773f12664877416ccbd))

feat: added conversation process config, ImportDocument and SuggestSmartReplies API

PiperOrigin-RevId: 423223164

Source-Link: https://github.com/googleapis/googleapis/commit/356f0c0439e04fc6b82215e75883bcc9f4263a04

Source-Link: https://github.com/googleapis/googleapis-gen/commit/72fe0202f4e3e91fe7a7a52ca248177261c2cc3f
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNzJmZTAyMDJmNGUzZTkxZmU3YTdhNTJjYTI0ODE3NzI2MWMyY2MzZiJ9

Release Google.Cloud.Dialogflow.V2 version 3.9.0 (#7704)


Changes in this release:

### New features

- Added export documentation method ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added filter in list documentations request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added option to import custom metadata from Google Cloud Storage in reload document request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added option to apply partial update to the smart messaging allowlist in reload document request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added filter in list knowledge bases request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Removed OPTIONAL for speech model variant ([commit 853d986](https://github.com/googleapis/google-cloud-dotnet/commit/853d98625a880a54c32b07d87f47924a7d65f84e))

### Documentation improvements

- Added more docs for speech model variant and improved docs format for participant ([commit 853d986](https://github.com/googleapis/google-cloud-dotnet/commit/853d98625a880a54c32b07d87f47924a7d65f84e))

chore: Regenerate all APIs to update copyright year

feat: added export documentation method feat: added filter in list documentations request feat: added option to import custom metadata from Google Cloud Storage in reload document request feat: added option to apply partial update to the smart messaging allowlist in reload document request feat: added filter in list knowledge bases request

PiperOrigin-RevId: 417030293

Source-Link: https://github.com/googleapis/googleapis/commit/ebef8e6c5ad95fcaa306935565086bed4ffbf663

Source-Link: https://github.com/googleapis/googleapis-gen/commit/13951268b009d98d82355ccd9647f4350590609d
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiMTM5NTEyNjhiMDA5ZDk4ZDgyMzU1Y2NkOTY0N2Y0MzUwNTkwNjA5ZCJ9

feat: removed OPTIONAL for speech model variant docs: added more docs for speech model variant and improved docs format for participant

PiperOrigin-RevId: 416079722

Source-Link: https://github.com/googleapis/googleapis/commit/14b7a25d42566b5b534f23a118c0ada5555e3d55

Source-Link: https://github.com/googleapis/googleapis-gen/commit/e1b0be15a7cd3466c46f0865835e714d1e9309fb
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZTFiMGJlMTVhN2NkMzQ2NmM0NmYwODY1ODM1ZTcxNGQxZTkzMDlmYiJ9

Release Google.Cloud.Dialogflow.V2 version 3.8.0 (#7544)


Changes in this release:

- [Commit d033f77](https://github.com/googleapis/google-cloud-dotnet/commit/d033f77): feat: support document metadata filter in article suggestion and smart reply model in human agent assistant

feat: support document metadata filter in article suggestion and smart reply model in human agent assistant

PiperOrigin-RevId: 409190373

Source-Link: https://github.com/googleapis/googleapis/commit/29bb98c1167ffc41e9771570e2e2d10a930baa4a

Source-Link: https://github.com/googleapis/googleapis-gen/commit/e90c22e9275b91aabc6c820a767af2fd6954f624
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiZTkwYzIyZTkyNzViOTFhYWJjNmM4MjBhNzY3YWYyZmQ2OTU0ZjYyNCJ9

Release Google.Cloud.Dialogflow.V2 version 3.7.0 (#7491)


Changes in this release:

- [Commit 6699f2e](https://github.com/googleapis/google-cloud-dotnet/commit/6699f2e): feat: added support to configure security settings, language code and time zone on conversation profile
- [Commit dd18efd](https://github.com/googleapis/google-cloud-dotnet/commit/dd18efd):
  - docs: clarified meaning of the legacy editions
  - docs: clarified semantic of the streaming APIs

feat: added support to configure security settings, language code and time zone on conversation profile

PiperOrigin-RevId: 407663596

Source-Link: https://github.com/googleapis/googleapis/commit/f9acb378c691a7ac449fd9fb32aa25aee14814d8

Source-Link: https://github.com/googleapis/googleapis-gen/commit/aa54a757068f005ab21064fb208a5ec597e49a9a
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiYWE1NGE3NTcwNjhmMDA1YWIyMTA2NGZiMjA4YTVlYzU5N2U0OWE5YSJ9

chore: Regenerate all APIs

This commit only contains code-generation attributes, validated via
"git diff" in conjunction with grep.

Release notes:
skip

docs: clarified meaning of the legacy editions docs: clarified semantic of the streaming APIs

PiperOrigin-RevId: 404815104

Source-Link: https://github.com/googleapis/googleapis/commit/bb1f3e9048c34528b3450cd0cb6faa91a6ee4b9f

Source-Link: https://github.com/googleapis/googleapis-gen/commit/79e2c39066f0616aa2dd6f07b0075ce3fb063b78
Copy-Tag: eyJwIjoiYXBpcy9Hb29nbGUuQ2xvdWQuRGlhbG9nZmxvdy5WMi8uT3dsQm90LnlhbWwiLCJoIjoiNzllMmMzOTA2NmYwNjE2YWEyZGQ2ZjA3YjAwNzVjZTNmYjA2M2I3OCJ9

Release Google.Cloud.Dialogflow.V2 version 3.6.0 (#7320)


Changes in this release:

- [Commit 03f91a3](https://github.com/googleapis/google-cloud-dotnet/commit/03f91a3): docs: recommend AnalyzeContent for future users

docs: recommend AnalyzeContent for future users

PiperOrigin-RevId: 402401837

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon Oct 11 15:05:36 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 16ff8131d5ee3aac50018069e91f80b60ee3caaa
Source-Link: https://github.com/googleapis/googleapis/commit/16ff8131d5ee3aac50018069e91f80b60ee3caaa

chore: Regenerate all non-OwlBot APIs with generator 1.3.11

This adds documentation for retriable status codes

Release Google.Cloud.Dialogflow.V2 version 3.5.0 (#7221)


Changes in this release:

- [Commit 6687459](https://github.com/googleapis/google-cloud-dotnet/commit/6687459): docs: clarified some LRO types
- [Commit ac367e2](https://github.com/googleapis/google-cloud-dotnet/commit/ac367e2): feat: Regenerate all APIs to support self-signed JWTs
- [Commit 0c649d8](https://github.com/googleapis/google-cloud-dotnet/commit/0c649d8): feat: expose `Locations` service to get/list avaliable locations of Dialogflow products; fixed some API annotations

chore: Rename all GrpcCtorCompatibility.g.cs files

These *are* generated files, but they're not part of the regular
generation process. They were generated once, and should effectively
be regarded as manually-curated at this point.

The generateapis.sh script *should* have been deleting these as
generated files, but a bug in the script is currently preventing it
from doing so. This change needs to go in before the script is fixed.

chore: Regenerate all APIs

Note that this does *not* regenerate Monitoring, as there's a
breaking change there that we're waiting on (see #7055) or
Google.Cloud.Audit which has broken dependencies (#7022).

The only changes are the application of GeneratedCodeAttribute.

docs: clarified some LRO types

PiperOrigin-RevId: 394302922

Source-Author: Google APIs <noreply@google.com>
Source-Date: Wed Sep 1 13:32:34 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: cd16abbf04752a0d2d1ae1c4050a36ba725fedd1
Source-Link: https://github.com/googleapis/googleapis/commit/cd16abbf04752a0d2d1ae1c4050a36ba725fedd1

Regenerate all APIs

Update all dependencies

feat: Add a LanguageCode to StreamingRecognitionResult

PiperOrigin-RevId: 389905442

Source-Author: Google APIs <noreply@google.com>
Source-Date: Tue Aug 10 09:35:17 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 4c984f3be8e1bd85eb8fe78a2911a83b9785a7ea
Source-Link: https://github.com/googleapis/googleapis/commit/4c984f3be8e1bd85eb8fe78a2911a83b9785a7ea
Release Google.Cloud.Dialogflow.V2 version 3.4.0

Changes in this release:

- [Commit 5dba1ca](https://github.com/googleapis/google-cloud-dotnet/commit/5dba1ca):
  - fix: fix validation result docs
  - feat: add language code to streaming recognition result
  - docs: update environment docs
- [Commit 281077c](https://github.com/googleapis/google-cloud-dotnet/commit/281077c): docs: fix typos

fix: fix validation result docs feat: add language code to streaming recognition result docs: update environment docs

PiperOrigin-RevId: 388737005

Source-Author: Google APIs <noreply@google.com>
Source-Date: Wed Aug 4 11:01:08 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 8dfb2156b61a0105b796cc76c657df392f1d091c
Source-Link: https://github.com/googleapis/googleapis/commit/8dfb2156b61a0105b796cc76c657df392f1d091c

docs: fix typos

PiperOrigin-RevId: 387960382

Source-Author: Google APIs <noreply@google.com>
Source-Date: Sat Jul 31 02:20:32 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 41521e288c8c2a4586dd46938bf574d0d36872e9
Source-Link: https://github.com/googleapis/googleapis/commit/41521e288c8c2a4586dd46938bf574d0d36872e9

Regenerate project files

Regenerate project files without Copyright property

Release Google.Cloud.Dialogflow.V2 version 3.3.0

Changes in this release:

- [Commit c135978](https://github.com/googleapis/google-cloud-dotnet/commit/c135978): docs: added notes to train agent prior to sending queries fix: added resource reference to agent_version
- [Commit 6567bfc](https://github.com/googleapis/google-cloud-dotnet/commit/6567bfc): feat: added Automated agent reply type and allow cancellation flag for partial response feature.
- [Commit b270512](https://github.com/googleapis/google-cloud-dotnet/commit/b270512): feat: added a field in the query result to indicate whether slot filling is cancelled.
- [Commit fe36e1e](https://github.com/googleapis/google-cloud-dotnet/commit/fe36e1e): feat: added location-aware HTTP path binding for ListIntents
- [Commit b782110](https://github.com/googleapis/google-cloud-dotnet/commit/b782110): fix: removed incorrect resource annotation for UpdateEnvironmentRequest.
- [Commit 88a63a8](https://github.com/googleapis/google-cloud-dotnet/commit/88a63a8):
  - feat: added more Environment RPCs
  - feat: added Versions service
  - feat: added Fulfillment service
  - feat: added TextToSpeechSettings.
  - feat: added location in some resource patterns.

docs: added notes to train agent prior to sending queries fix: added resource reference to agent_version

PiperOrigin-RevId: 380595849

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon Jun 21 09:28:51 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 5fe3c6322046ed5cfc41e6c41c7ebac54db589dd
Source-Link: https://github.com/googleapis/googleapis/commit/5fe3c6322046ed5cfc41e6c41c7ebac54db589dd

feat: added Automated agent reply type and allow cancellation flag for partial response feature.

PiperOrigin-RevId: 379370373

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon Jun 14 16:21:54 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 58187afe44fbbe89dec2b70b6c2b405f88b7d295
Source-Link: https://github.com/googleapis/googleapis/commit/58187afe44fbbe89dec2b70b6c2b405f88b7d295

feat: added a field in the query result to indicate whether slot filling is cancelled.

PiperOrigin-RevId: 375489925

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon May 24 09:19:41 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: a185afb98265e13f1310e428ea5798470b24882a
Source-Link: https://github.com/googleapis/googleapis/commit/a185afb98265e13f1310e428ea5798470b24882a

feat: added location-aware HTTP path binding for ListIntents

PiperOrigin-RevId: 373895026

Source-Author: Google APIs <noreply@google.com>
Source-Date: Fri May 14 17:14:27 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 0d68bbb80a7620b69aff5ab0b497c8a396e73558
Source-Link: https://github.com/googleapis/googleapis/commit/0d68bbb80a7620b69aff5ab0b497c8a396e73558

fix: removed incorrect resource annotation for UpdateEnvironmentRequest.

PiperOrigin-RevId: 372225073

Source-Author: Google APIs <noreply@google.com>
Source-Date: Wed May 5 15:54:49 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 2f749e7155fbfcab85aa0f169da78313536a5ee0
Source-Link: https://github.com/googleapis/googleapis/commit/2f749e7155fbfcab85aa0f169da78313536a5ee0

feat: added more Environment RPCs feat: added Versions service feat: added Fulfillment service feat: added TextToSpeechSettings. feat: added location in some resource patterns.

PiperOrigin-RevId: 371848474

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon May 3 22:56:28 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 5efeb79eed444f14cf2cf89516dbf9ece86a4a0c
Source-Link: https://github.com/googleapis/googleapis/commit/5efeb79eed444f14cf2cf89516dbf9ece86a4a0c

Release Google.Cloud.Dialogflow.V2 version 3.2.0

Changes in this release:

- [Commit ae565e2](https://github.com/googleapis/google-cloud-dotnet/commit/ae565e2): feat: expose MP3_64_KBPS and MULAW for output audio encodings.
- [Commit a6aa034](https://github.com/googleapis/google-cloud-dotnet/commit/a6aa034):
  - docs: fix link for version and environment in participant doc.
  - fix: Add all missing regional HTTP bindings in DF API.
- [Commit 79f24ea](https://github.com/googleapis/google-cloud-dotnet/commit/79f24ea): feat: Add CCAI API
- [Commit 14e6a6c](https://github.com/googleapis/google-cloud-dotnet/commit/14e6a6c):
  - feat: add additional_bindings to Dialogflow v2 ListIntents API
  - docs: update copyrights and session docs
- [Commit 6e5f4f6](https://github.com/googleapis/google-cloud-dotnet/commit/6e5f4f6): docs: update comments on parameters and validation result.
- [Commit 9900407](https://github.com/googleapis/google-cloud-dotnet/commit/9900407):
  - feat: allowed custom to specify webhook headers through query parameters
  - docs: suggested to always use version for production traffic when calling DetectIntent, mark match_mode in Agent message as deprecated

Regenerate all APIs with newer gRPC generator

Regenerate all APIs with the new script

(synth.metadata files were reverted)

feat: expose MP3_64_KBPS and MULAW for output audio encodings.

PiperOrigin-RevId: 364696134

Source-Author: Google APIs <noreply@google.com>
Source-Date: Tue Mar 23 18:45:59 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: c2bdbfa6f7423369da902a5faaa86bfd213b5169
Source-Link: https://github.com/googleapis/googleapis/commit/c2bdbfa6f7423369da902a5faaa86bfd213b5169

docs: fix link for version and environment in participant doc. fix: Add all missing regional HTTP bindings in DF API.

PiperOrigin-RevId: 364356707

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon Mar 22 10:50:15 2021 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 5ef92c3f11395a59f55ced317423b992e61d5cfe
Source-Link: https://github.com/googleapis/googleapis/commit/5ef92c3f11395a59f55ced317423b992e61d5cfe

feat: Add CCAI API

feat: add additional_bindings to Dialogflow v2 ListIntents API docs: update copyrights and session docs

PiperOrigin-RevId: 358315519

Source-Author: Google APIs <noreply@google.com>
Source-Date: Thu Feb 18 19:08:57 2021 -0800
Source-Repo: googleapis/googleapis
Source-Sha: 54020365f5a790dcff0bbcff5643adea2a199ccb
Source-Link: https://github.com/googleapis/googleapis/commit/54020365f5a790dcff0bbcff5643adea2a199ccb

Regenerate all projects with updated copyright year

Regenerate all APIs to update copyright year

The following command shows no changes:

```text
git diff --cached --unified=0 | \
  grep -v '"sha"' | \
  grep -v Copyright | \
  grep -v '\-\-\-' | \
  grep -v '+++' | \
  grep -v @@ | \
  grep -v "diff --git" | \
  grep -v -E '^index'
```

That basically accounts for:

- SHA differences in synth.metadata files
- Copyright differences
- All the additional context that git diff provides

docs: update comments on parameters and validation result.

PiperOrigin-RevId: 348673154

Source-Author: Google APIs <noreply@google.com>
Source-Date: Tue Dec 22 12:11:37 2020 -0800
Source-Repo: googleapis/googleapis
Source-Sha: 0795e3f854056696f330454023b9fa6d35053b79
Source-Link: https://github.com/googleapis/googleapis/commit/0795e3f854056696f330454023b9fa6d35053b79

Webhook headers, and docs

feat: allowed custom to specify webhook headers through query parameters
docs: suggested to always use version for production traffic when calling DetectIntent, mark match_mode in Agent message as deprecated

PiperOrigin-RevId: 345742559

Source-Author: Google APIs <noreply@google.com>
Source-Date: Fri Dec 4 13:15:39 2020 -0800
Source-Repo: googleapis/googleapis
Source-Sha: 519e9dcdff23cc14d48f85e9e00b6214ec57967e
Source-Link: https://github.com/googleapis/googleapis/commit/519e9dcdff23cc14d48f85e9e00b6214ec57967e
Release Google.Cloud.Dialogflow.V2 version 3.1.0

Changes in this release:

- [Commit 079e919](https://github.com/googleapis/google-cloud-dotnet/commit/079e919): docs: fixed link from SentimentAnalysisResult
- [Commit 0790924](https://github.com/googleapis/google-cloud-dotnet/commit/0790924): fix: Add gRPC compatibility constructors
- [Commit 0ca05f5](https://github.com/googleapis/google-cloud-dotnet/commit/0ca05f5): chore: Regenerate all APIs using protoc 3.13 and Grpc.Tools 2.31
- [Commit 0cdabf1](https://github.com/googleapis/google-cloud-dotnet/commit/0cdabf1): docs: wording updates for tiers.
- [Commit ebd848c](https://github.com/googleapis/google-cloud-dotnet/commit/ebd848c): docs: more detailed docs on APIs such as Environment, Intents, Sessions.
- [Commit c552537](https://github.com/googleapis/google-cloud-dotnet/commit/c552537): docs: Regenerate Dialogflow V2 with cleaner docs
- [Commit 6bde7a3](https://github.com/googleapis/google-cloud-dotnet/commit/6bde7a3): docs: Regenerate all APIs with service comments in client documentation
- [Commit 34c92e6](https://github.com/googleapis/google-cloud-dotnet/commit/34c92e6):
  - fix: Update grpc config for retry mechanism.
  - docs: Update ImportAgent/ExportAgent external documentation.
- [Commit f83bdf1](https://github.com/googleapis/google-cloud-dotnet/commit/f83bdf1): fix: Apply timeouts to RPCs without retry
- [Commit 2bac8ab](https://github.com/googleapis/google-cloud-dotnet/commit/2bac8ab): docs: cleaned docs for the Agents service and resource.

docs: fixed link from SentimentAnalysisResult

PiperOrigin-RevId: 336344634

Source-Author: Google APIs <noreply@google.com>
Source-Date: Fri Oct 9 12:36:01 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: fd31b1600fc496d6127665d29f095371d985c637
Source-Link: https://github.com/googleapis/googleapis/commit/fd31b1600fc496d6127665d29f095371d985c637

Add gRPC compatibility constructors

Regenerate all APIs using protoc 3.13 and Grpc.Tools 2.31

Note that the change in gRPC generation is *just possibly* breaking,
as it changes a constructor parameter type (to a base type). This is
far less likely to break anyone than changing a *method* parameter,
as method group conversions aren't involved. It also removes the
dependency on Grpc.Core from the generated code.

Regenerate project files

Regenerate all APIs with updated generator

The only relevant change is to enums: we now generate a comma after all enum members, including the last one.

docs: wording updates for tiers.

PiperOrigin-RevId: 331189912

Source-Author: Google APIs <noreply@google.com>
Source-Date: Fri Sep 11 11:38:58 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: b100ad424293ce5d5378e9067d9d83c4973a115a
Source-Link: https://github.com/googleapis/googleapis/commit/b100ad424293ce5d5378e9067d9d83c4973a115a

chore: no-op change

PiperOrigin-RevId: 323436667

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon Jul 27 14:05:51 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 546f389d95dbbc88d9d5a00fae25b29d49a0d5b6
Source-Link: https://github.com/googleapis/googleapis/commit/546f389d95dbbc88d9d5a00fae25b29d49a0d5b6
docs: more detailed docs on APIs such as Environment, Intents, Sessions.

PiperOrigin-RevId: 323086730

Source-Author: Google APIs <noreply@google.com>
Source-Date: Fri Jul 24 15:42:41 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: a6b2dac798ed266136e990a2319b2e2e96f3bdbe
Source-Link: https://github.com/googleapis/googleapis/commit/a6b2dac798ed266136e990a2319b2e2e96f3bdbe

Regenerate Dialogflow V2 with cleaner docs

Regenerate all APIs with service comments in client documentation

The comments are included as they are, as a "remarks" section both the abstract base class and the concrete implementation.

- Update grpc config for retry mechanism. - Update ImportAgent/ExportAgent external documentation.

PiperOrigin-RevId: 317902626

Source-Author: Google APIs <noreply@google.com>
Source-Date: Tue Jun 23 11:09:31 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 4e8f1142ff921de8d5ad757bce9f2c09dab6ff1b
Source-Link: https://github.com/googleapis/googleapis/commit/4e8f1142ff921de8d5ad757bce9f2c09dab6ff1b

Regenerate all APIs with generator changes

This effectively applies
https://github.com/googleapis/gapic-generator-csharp/pull/257, which
enables RPCs without retries to still have timeouts specified.

It is expected that change (along with synth.metadata changes) should
be the *only* change in this PR.

docs: cleaned docs for the Agents service and resource.

PiperOrigin-RevId: 314879617

Source-Author: Google APIs <noreply@google.com>
Source-Date: Fri Jun 5 00:27:22 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: cd804bab06e46dd1a4f16c32155fd3cddb931b52
Source-Link: https://github.com/googleapis/googleapis/commit/cd804bab06e46dd1a4f16c32155fd3cddb931b52

Release Google.Cloud.Dialogflow.V2 version 3.0.0

Changes in this release:

Documentation changes only since 3.0.0-beta02:

- [Commit 4181b4f](https://github.com/googleapis/google-cloud-dotnet/commit/4181b4f): docs: Comment updates only
- [Commit 947a573](https://github.com/googleapis/google-cloud-dotnet/commit/947a573): docs: Regenerate all clients with more explicit documentation
- [Commit b3e7794](https://github.com/googleapis/google-cloud-dotnet/commit/b3e7794): docs: minor comments change.

As noted in the 3.0.0-beta01 history, 3.0.0 is a breaking change compared with 2.0.0 due to resource names being corrected.

docs: Comment updates only (#4977)

PiperOrigin-RevId: 312123588

Source-Author: Google APIs <noreply@google.com>
Source-Date: Mon May 18 11:49:18 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: cd3ce2651c3921670217e664303976cdf76e9fe2
Source-Link: https://github.com/googleapis/googleapis/commit/cd3ce2651c3921670217e664303976cdf76e9fe2
Regenerate all clients with more explicit documentation

The use of "inheritdoc" breaks docfx in many cases. The generator
has been improved to generate more explicit documentation. This PR only
contains changes due to that generator change.

docs: minor comments change.

PiperOrigin-RevId: 309481123

Source-Author: Google APIs <noreply@google.com>
Source-Date: Fri May 1 15:04:46 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: ee9e8e4e67f06aba881392a1a2956fbe7a42d216
Source-Link: https://github.com/googleapis/googleapis/commit/ee9e8e4e67f06aba881392a1a2956fbe7a42d216

Release Google.Cloud.Dialogflow.V2 version 3.0.0-beta02

Changes in this release:

- [Commit 610cf69](https://github.com/googleapis/google-cloud-dotnet/commit/610cf69):
  - feat: Publish ListEnvironments
  - docs: Clarify WebhookResponse fields
- [Commit f2f7630](https://github.com/googleapis/google-cloud-dotnet/commit/f2f7630): docs: Update comments on Contexts and Sessions resources.

feat: Publish ListEnvironments for Dialogflow v2/v2beta1 library.
docs: Clarify WebhookResponse fields for Dialogflow v2/v2beta1 library.

PiperOrigin-RevId: 307849529

Source-Author: Google APIs <noreply@google.com>
Source-Date: Wed Apr 22 10:48:21 2020 -0700
Source-Repo: googleapis/googleapis
Source-Sha: 1d520eaa7bbd8b40f53942ff03b5496fff887b53
Source-Link: https://github.com/googleapis/googleapis/commit/1d520eaa7bbd8b40f53942ff03b5496fff887b53

Regenerate all projects

Regenerate all project files

Regenerate all project files using major-pinned dependencies where appropriate

Dialogflow weekly v2/v2beta1 library update:

Source-Repo: googleapis/googleapis
Source-Sha: 1e92c343790ae63f88817afde60bd2d5bc775f36
Source-Link: https://github.com/googleapis/googleapis/commit/1e92c343790ae63f88817afde60bd2d5bc775f36
Author: Google APIs <noreply@google.com>
Date: Fri Apr 10 12:09:05 2020 -0700
Original-Commit-Message: Dialogflow weekly v2/v2beta1 library update:
- Update comments on Contexts and Sessions resources.

PiperOrigin-RevId: 305919798

Release Google.Cloud.Dialogflow.V2 version 3.0.0-beta01

Changes in this release:

- [Commit 5a41fb5](https://github.com/googleapis/google-cloud-dotnet/commit/5a41fb5):
  - Change `parent` field's resource_reference to specify child_type instead of type per client library generation requirement;
  - Change Session with its child resource pattern to support both projects/{project}/agent/sessions/{session} and projects/{project}/agent/environments/{environment}/users/{user}/sessions/{session};
  - Fix `method_signature`
  - Regular documentation update

This is a breaking change in terms of resource names, which weren't
correctly defined in the API before. We will release a new GA
version once we're satisfied that no further breaking changes will
be required.

Dialogflow weekly v2 library update

Dialogflow weekly v2 library update

- Change `parent` field's resource_reference to specify child_type instead of type per client library generation requirement;
- Change Session with its child resource pattern to support both projects/{project}/agent/sessions/{session} and projects/{project}/agent/environments/{environment}/users/{user}/sessions/{session};
- Fix `method_signature`
- Regular documentation update

googleapis/googleapis@3d52f3c
commit 3d52f3c126fbfc31f067a7f54737b7f0dfbce163
Author: Google APIs <noreply@google.com>
Date:   Fri Apr 3 09:48:52 2020 -0700

    Dialogflow weekly v2 library update:
    - Change `parent` field's resource_reference to specify child_type instead of type per client library generation requirement;
    - Change Session with its child resource pattern to support both projects/{project}/agent/sessions/{session} and projects/{project}/agent/environments/{environment}/users/{user}/sessions/{session};
    - Fix `method_signature`
    - Regular documentation update

    Important updates are also posted at:
    https://cloud.google.com/dialogflow/docs/release-notes

    PiperOrigin-RevId: 304635286
Release Google.Cloud.Dialogflow.V2 version 2.0.0

Changes in this release:

- [Commit a19ee13](https://github.com/googleapis/google-cloud-dotnet/commit/a19ee13):
  - Adds AgentsClient.GetValidationResult RPC with associated types
  - Adds DetectIntentRequest.OutputAudioConfigMask

Regenerate all projects

(Should have done this before. Oops.)

Regenerate project files

Regenerate projects

Regenerate all APIs to pick up generator changes

This commit only contains changes to the client builders, which now
have partial methods to allow interception of the Build/BuildAsync
methods.

Regenerate projects

Regenerate Google.Cloud.Dialogflow.V2 (#4438)

- Adds AgentsClient.GetValidationResult RPC with associated types
- Adds DetectIntentRequest.OutputAudioConfigMask
Regenerate all project files

Release Google.Cloud.Dialogflow.V2 version 2.0.0-beta01

This is the first prerelease targeting GAX v3. Please see the [breaking changes guide](https://googleapis.github.io/google-cloud-dotnet/docs/guides/breaking-gax2.html) for details of changes to both GAX and code generation.

Regenerate project files

Regenerate project files

Regenerate project files

Regenerate client builders with DefaultGrpcAdapter property

Regenerate all microgenerator APIs

This required a manual tweak to the KMS proto file, which I'm hoping to merge later today.

Some of these still won't build due to changes required to manual code - those changes will be in later commits.

Regenerate all APIs

This will pull in multiple microgenerator API changes, including:

- Resource name redesign (with factory methods, and better multipattern support)
- The updated GAX retry settings
- The use of WithGoogleRequestParam instead of WithCallSettingsOverlay
- Exclusing obsolete properties from snippets and tests

Regenerate Dialogflow.V2

Migrate Dialogflow.V2 to the microgenerator

Regenerate projects

Regenerate all micro-generated APIs

This just changes the retry settings in line with the new CallSettings structure in GAX.

Still to do:

- Any manual code using timing
- Monolithic generated code

Changes in generated code (manually or automatically applied) for GAX v3

Update to Grpc.Core 2.25.0

Regenerate projects

Regenerate Google.Cloud.Dialogflow.V2 (#4226)

Make LanguageCode optional in many requests
Regenerate Google.Cloud.Dialogflow.V2 (#4224)

Comment-only change
Regenerate Google.Cloud.Dialogflow.V2 (#4216)

Docs and resource annotations.
Regenerate Google.Cloud.Dialogflow.V2 (#4172)

Just documentation comment changes.
Update copyright notice in all non-microgenerator APIs

Regenerate Google.Cloud.Dialogflow.V2 (#4071)

Descriptor-only changes
Update copyright notices (autogenerated)

Regenerate Google.Cloud.Dialogflow.V2 (#3976)

Expands speech recognition information:

- Input allows the model, speech contexts and phrase hints to be specified, and word info to be requested
- Output includes word info and the end of speech
Regenerate Google.Cloud.Dialogflow.V2 (#3973)

Descriptor-only change
Release Google.Cloud.Dialogflow.V2 version 1.2.0

Changes since 1.1.0:

- [Commit 532f28b](https://github.com/googleapis/google-cloud-dotnet/commit/532f28b): Multiple new features:
  - Intent.BrowseCarouselCard
  - Intent.MediaContent
  - Intent.TableCard
- [Commit c8a6431](https://github.com/googleapis/google-cloud-dotnet/commit/c8a6431): Added ListSelect.Subtitle

Regenerate Google.Cloud.Dialogflow.V2 (#3755)

Comment updates.

## Version 4.26.0, released 2025-03-10

### New features

- Add new RPC IngestContextReferences, GenerateSuggestions ([commit 449b11f](https://github.com/googleapis/google-cloud-dotnet/commit/449b11fdbf523e78cecdb8d1798393aab03c1c50))
- Added support for TelephonyConnectionInfo, country_code and ControlPoint ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Added support for CONVERSATION_SUMMARIZATION ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Added ConversatioalTrainingAssignments, ConversationalTrainingMembers, ConversationalTrainingModules,ConversationalTrainingTeams API ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Added support for audio_input and speech_model ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Changed enablle_partial_automated_agent_reply to optional ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))

### Documentation improvements

- Clarified wording around phrase_sets ([commit 449b11f](https://github.com/googleapis/google-cloud-dotnet/commit/449b11fdbf523e78cecdb8d1798393aab03c1c50))
- Clarified wording around filter and document_correctness ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Clarified wording around use_timeout_based_endpointing ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Changed reference link around ConversationStage ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Clarified wording around boost_specs and filter_specs ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))
- Clarified wording around send_time ([commit 57d2148](https://github.com/googleapis/google-cloud-dotnet/commit/57d2148d5f3f797ff8524588a5c90ff2ef121565))

## Version 4.25.0, released 2024-12-16

### New features

- Add new fields for delivering intermediate transcriptions through PubSub ([commit b94ea2a](https://github.com/googleapis/google-cloud-dotnet/commit/b94ea2a6f6ca0d2551c7471c018da65ee381f65c))

## Version 4.24.0, released 2024-12-06

### New features

- Properly mark TrainingPhrase name field output-only ([commit d336935](https://github.com/googleapis/google-cloud-dotnet/commit/d336935d53910959377f0437f88cee1f1577ebf9))

### Documentation improvements

- Fixed the references to proto method / fields ([commit d336935](https://github.com/googleapis/google-cloud-dotnet/commit/d336935d53910959377f0437f88cee1f1577ebf9))

## Version 4.23.0, released 2024-11-18

### New features

- Add options of query_source, search_config, end_user_metadata and exact_search ([commit a08e4da](https://github.com/googleapis/google-cloud-dotnet/commit/a08e4da2ff37af2a1097ff51e91c694f4b445515))
- Expose metadata in AnswerSource ([commit a08e4da](https://github.com/googleapis/google-cloud-dotnet/commit/a08e4da2ff37af2a1097ff51e91c694f4b445515))
- Added support for ALAW encoding ([commit b206f21](https://github.com/googleapis/google-cloud-dotnet/commit/b206f2191e4dcf31df81e2d540ab4ed3bc5c8fb7))
- Add options of query_source, search_config and context_size ([commit b206f21](https://github.com/googleapis/google-cloud-dotnet/commit/b206f2191e4dcf31df81e2d540ab4ed3bc5c8fb7))

## Version 4.22.0, released 2024-09-26

### New features

- Created new boolean fields in conversation dataset for zone isolation and zone separation compliance status ([commit 1a9f58d](https://github.com/googleapis/google-cloud-dotnet/commit/1a9f58dd2cf7690fc50ec780c2f573ccda43eccb))
- Add ALAW encoding value to Audio encoding enum ([commit 1a9f58d](https://github.com/googleapis/google-cloud-dotnet/commit/1a9f58dd2cf7690fc50ec780c2f573ccda43eccb))
- Created new boolean fields in conversation model for zone isolation and zone separation compliance status ([commit 24e7f8f](https://github.com/googleapis/google-cloud-dotnet/commit/24e7f8f17a28c721b9eae24260db021a42292583))

## Version 4.21.0, released 2024-08-05

### Bug fixes

- Changed field behavior for an existing field `parent` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- Changed field behavior for an existing field `session_id` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))

### New features

- Add Proactive Generative Knowledge Assist endpoints and types ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- Add Generator related services and types ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- Add GenerateStatelessSuggestion related endpoints and types ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))

### Documentation improvements

- A comment for field `name` in message `.google.cloud.dialogflow.v2.Conversation` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `conversation_stage` in message `.google.cloud.dialogflow.v2.Conversation` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `filter` in message `.google.cloud.dialogflow.v2.ListConversationsRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `context_size` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `assist_query_params` in message `.google.cloud.dialogflow.v2.SuggestConversationSummaryRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.GenerateStatelessSummaryRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `max_context_size` in message `.google.cloud.dialogflow.v2.GenerateStatelessSummaryRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `parent` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `session_id` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `conversation` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `latest_message` in message `.google.cloud.dialogflow.v2.SearchKnowledgeRequest` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for message `HumanAgentHandoffConfig` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `live_person_config` in message `.google.cloud.dialogflow.v2.HumanAgentHandoffConfig` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))
- A comment for field `audio` in message `.google.cloud.dialogflow.v2.AudioInput` is changed ([commit b56beb4](https://github.com/googleapis/google-cloud-dotnet/commit/b56beb4b533d546023e44cec994d1ec3cd93b953))

## Version 4.20.0, released 2024-06-04

### New features

- Add properties for nested resource name references ([commit 15eec4d](https://github.com/googleapis/google-cloud-dotnet/commit/15eec4dabb9fd3cf3b8f4b978d64b7ba435ca995))

## Version 4.19.0, released 2024-05-13

### New features

- Add IServiceCollection extension methods for client registration where an IServiceProvider is required. ([commit 022fab2](https://github.com/googleapis/google-cloud-dotnet/commit/022fab203f28fb9c608972af7f8b83f571ae5694))

## Version 4.18.0, released 2024-03-26

### New features

- Change netstandard2.1 target to netstandard2.0 ([commit 82bea85](https://github.com/googleapis/google-cloud-dotnet/commit/82bea850661975b9750ac30753528cc9d2e05240))

## Version 4.17.0, released 2024-03-21

### New features

- Added text sections to the submitted summary ([commit 720a6ad](https://github.com/googleapis/google-cloud-dotnet/commit/720a6ad8a0c11a7a7d386208b22f04c1afa48769))
- Added conformer model migration opt out flag ([commit 720a6ad](https://github.com/googleapis/google-cloud-dotnet/commit/720a6ad8a0c11a7a7d386208b22f04c1afa48769))

### Documentation improvements

- Clarified wording around END_OF_SINGLE_UTTERANCE ([commit 720a6ad](https://github.com/googleapis/google-cloud-dotnet/commit/720a6ad8a0c11a7a7d386208b22f04c1afa48769))

## Version 4.16.0, released 2024-02-28

No API surface changes; just dependency updates.

## Version 4.15.0, released 2024-01-08

### New features

- Add sections field to HumanAgentAssistantConfig.SuggestionQueryConfig ([commit 9dcd3d1](https://github.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))
- Add enable_conversation_augmented_query field to HumanAgentAssistantConfig.SuggestionFeatureConfig message ([commit 9dcd3d1](https://github.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))
- Add INTENT enum in SearchKnowledgeAnswer.AnswerType message ([commit 9dcd3d1](https://github.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))
- Add rewritten_query in field in SearchKnowledgeResponse message ([commit 9dcd3d1](https://github.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))

### Documentation improvements

- Improved comments on audio_config proto ([commit 9dcd3d1](https://github.com/googleapis/google-cloud-dotnet/commit/9dcd3d1679ebe9c9a31f422499c23d92ac45c69b))

## Version 4.14.0, released 2023-10-02

### New features

- Add the enable_extended_streaming flag ([commit 7db6a56](https://github.com/googleapis/google-cloud-dotnet/commit/7db6a5666de3ea07b6321f28e5df8dc42db2097d))

## Version 4.13.0, released 2023-09-06

### New features

- Added speech endpointing setting ([commit b08f369](https://github.com/googleapis/google-cloud-dotnet/commit/b08f369651e6a6877f9527f3b5c881bc34f1ead9))
- Added Knowledge Search API ([commit b08f369](https://github.com/googleapis/google-cloud-dotnet/commit/b08f369651e6a6877f9527f3b5c881bc34f1ead9))

## Version 4.12.0, released 2023-08-16

### New features

- Added baseline model version used to generate the summary ([commit 561a1e0](https://github.com/googleapis/google-cloud-dotnet/commit/561a1e0215af68aa92c4ff57a1b863e8f8dde700))
- Added the platform of the virtual agent response messages ([commit 561a1e0](https://github.com/googleapis/google-cloud-dotnet/commit/561a1e0215af68aa92c4ff57a1b863e8f8dde700))

### Documentation improvements

- Minor formatting ([commit 388c3e2](https://github.com/googleapis/google-cloud-dotnet/commit/388c3e2e054dc58062aa1ea7b24c5e613456defc))
- Minor formatting ([commit 7648d13](https://github.com/googleapis/google-cloud-dotnet/commit/7648d133650b0ae986da702d4948dcef308221bb))
- Added google.api.field_behavior for some fields in audio_config ([commit 8588148](https://github.com/googleapis/google-cloud-dotnet/commit/858814847ba8e5b7f6ca123cc8f806db2742d375))

## Version 4.11.0, released 2023-06-27

### New features

- Added dialogflow_assist_answer ([commit 4d022ec](https://github.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added session_ttl ([commit 4d022ec](https://github.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added human_agent_side_config ([commit 4d022ec](https://github.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added suggestion_input ([commit 4d022ec](https://github.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added suggest_dialogflow_assists_response ([commit 4d022ec](https://github.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))
- Added suggest_entity_extraction_response ([commit 4d022ec](https://github.com/googleapis/google-cloud-dotnet/commit/4d022ec34890706a7efdbdacbf8e6f4f3d348b5e))

## Version 4.10.0, released 2023-05-11

### New features

- Add baseline model configuration for conversation summarization ([commit fe578a7](https://github.com/googleapis/google-cloud-dotnet/commit/fe578a7cbccdebc73b5c3dae63efd9be68a38298))
- Extended StreamingListCallCompanionEvents timeout to 600 seconds ([commit ddd7f08](https://github.com/googleapis/google-cloud-dotnet/commit/ddd7f0877f1fb600eb42a5e169525a37b6dd99c0))
- Added debug info for StreamingDetectIntent ([commit ddd7f08](https://github.com/googleapis/google-cloud-dotnet/commit/ddd7f0877f1fb600eb42a5e169525a37b6dd99c0))
- Added GenerateStatelessSummary method ([commit ddd7f08](https://github.com/googleapis/google-cloud-dotnet/commit/ddd7f0877f1fb600eb42a5e169525a37b6dd99c0))

## Version 4.9.0, released 2023-03-06

### New features

- Added support for custom content types ([commit 15d6a43](https://github.com/googleapis/google-cloud-dotnet/commit/15d6a439b9d0c204c1b60751848318ccd69f3358))

### Documentation improvements

- Clarified wording around quota usage ([commit 15d6a43](https://github.com/googleapis/google-cloud-dotnet/commit/15d6a439b9d0c204c1b60751848318ccd69f3358))

## Version 4.8.0, released 2023-02-22

### New features

- Added support for AssistQueryParameters and SynthesizeSpeechConfig ([commit 22e5419](https://github.com/googleapis/google-cloud-dotnet/commit/22e5419cf66c7db39753a3c17588fa5324eb7bfe))

### Documentation improvements

- Add more meaningful comments ([commit 22e5419](https://github.com/googleapis/google-cloud-dotnet/commit/22e5419cf66c7db39753a3c17588fa5324eb7bfe))

## Version 4.7.0, released 2023-01-19

### New features

- Enable REST transport in C# ([commit 496c8ab](https://github.com/googleapis/google-cloud-dotnet/commit/496c8abe53e80646e5dd5a6d4a2231b11b36969a))

## Version 4.6.0, released 2023-01-16

### New features

- Added SuggestConversationSummary RPC ([commit 833acec](https://github.com/googleapis/google-cloud-dotnet/commit/833acec549980676e804fab02b422be55ddcbc5f))

### Documentation improvements

- Updated go library package ([commit 833acec](https://github.com/googleapis/google-cloud-dotnet/commit/833acec549980676e804fab02b422be55ddcbc5f))

## Version 4.5.0, released 2022-12-01

### New features

- Added cx_current_page field to AutomatedAgentReply ([commit 2e15dd1](https://github.com/googleapis/google-cloud-dotnet/commit/2e15dd164b6552055ea6c9f2ba23f8b9e75959f3))

### Documentation improvements

- Clarified docs for Sentiment ([commit 2e15dd1](https://github.com/googleapis/google-cloud-dotnet/commit/2e15dd164b6552055ea6c9f2ba23f8b9e75959f3))

## Version 4.4.0, released 2022-11-02

### New features

- Added StreamingAnalyzeContent API ([commit bdfcd9e](https://github.com/googleapis/google-cloud-dotnet/commit/bdfcd9e76fbd1ff7e47bd590bdf073749a088568))
- Added obfuscated_external_user_id to Participant ([commit bdfcd9e](https://github.com/googleapis/google-cloud-dotnet/commit/bdfcd9e76fbd1ff7e47bd590bdf073749a088568))
- Can directly set Cloud Speech model on the SpeechToTextConfig ([commit bdfcd9e](https://github.com/googleapis/google-cloud-dotnet/commit/bdfcd9e76fbd1ff7e47bd590bdf073749a088568))

## Version 4.3.0, released 2022-10-17

### New features

- Include conversation dataset name to be created with dataset creation metadata ([commit 293e1ff](https://github.com/googleapis/google-cloud-dotnet/commit/293e1ff997ea8ccedf5812dda0392089cfbe8228))

### Documentation improvements

- Clarify SuggestionFeature enums which are specific to chat agents ([commit 293e1ff](https://github.com/googleapis/google-cloud-dotnet/commit/293e1ff997ea8ccedf5812dda0392089cfbe8228))

## Version 4.2.0, released 2022-09-15

### Documentation improvements

- Added an explicit note that DetectIntentRequest's text input is limited by 256 characters ([commit 0fd3a71](https://github.com/googleapis/google-cloud-dotnet/commit/0fd3a71d2b6bead1e2fb0e0761add19f4785d2ee))

## Version 4.1.0, released 2022-07-11

### New features

- Deprecated the filter field and add resource_definition ([commit 05d7b7b](https://github.com/googleapis/google-cloud-dotnet/commit/05d7b7b5e149a6bcf813db29a787b77902b28326))

### Documentation improvements

- Add more meaningful comments ([commit 05d7b7b](https://github.com/googleapis/google-cloud-dotnet/commit/05d7b7b5e149a6bcf813db29a787b77902b28326))

## Version 4.0.0, released 2022-06-08

This is the first version of this package to depend on GAX v4.

There are some breaking changes, both in GAX v4 and in the generated
code. The changes that aren't specific to any given API are [described in the Google Cloud
documentation](https://cloud.google.com/dotnet/docs/reference/help/breaking-gax4).
We don't anticipate any changes to most customer code, but please [file a
GitHub issue](https://github.com/googleapis/google-cloud-dotnet/issues/new/choose)
if you run into problems.

The most important change in this release is the use of the Grpc.Net.Client package
for gRPC communication, instead of Grpc.Core. When using .NET Core 3.1 or .NET 5.0+
this should lead to a smaller installation footprint and greater compatibility (e.g.
with Apple M1 chips). Any significant change in a core component comes with the risk
of incompatibility, however - so again, please let us know if you encounter any
issues.

### API-specific Breaking changes

- Correct broken ConversationModelEvaluation resource pattern ([commit 52734a8](https://github.com/googleapis/google-cloud-dotnet/commit/52734a83d8a941fc01978bffe260ea60bbbd27fb))

### Documentation improvements

- Add the fields for setting CX virtual agent session parameters ([commit f697491](https://github.com/googleapis/google-cloud-dotnet/commit/f69749149a6c84e32e18a50aacbc3b7ad838774f))
- Added explanation for SuggestionResult ([commit 15b7174](https://github.com/googleapis/google-cloud-dotnet/commit/15b717491e9a3458e4b396e472a3503e49acf150))

## Version 3.11.0, released 2022-03-14

### New features

- Added ConversationModel resource and its APIs ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added ConversationDataset resource and its APIs ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added SetSuggestionFeatureConfig and ClearSuggestionFeatureConfig APIs for ConversationProfile ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added new knowledge type of Document content ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added states of Document ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))
- Added metadata for the Knowledge operation ([commit 300879d](https://github.com/googleapis/google-cloud-dotnet/commit/300879d8386f30331c7f2e5a3c04b3cb78043aaa))

### Documentation improvements

- Clarified the behavior of language_code in EventInput in the context of a followup event input ([commit 3449846](https://github.com/googleapis/google-cloud-dotnet/commit/3449846a23e7806e98db432bfcb00f52eee8b838))
- Clarified wording around Cloud Storage usage ([commit 3449846](https://github.com/googleapis/google-cloud-dotnet/commit/3449846a23e7806e98db432bfcb00f52eee8b838))
- Added a new resource name pattern for ConversationModel ([commit 3449846](https://github.com/googleapis/google-cloud-dotnet/commit/3449846a23e7806e98db432bfcb00f52eee8b838))
## Version 3.10.0, released 2022-02-07

### New features

- Added conversation process config, ImportDocument and SuggestSmartReplies API ([commit 7d25d83](https://github.com/googleapis/google-cloud-dotnet/commit/7d25d8374eee6a36251e1773f12664877416ccbd))

## Version 3.9.0, released 2022-01-17

### New features

- Added export documentation method ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added filter in list documentations request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added option to import custom metadata from Google Cloud Storage in reload document request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added option to apply partial update to the smart messaging allowlist in reload document request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Added filter in list knowledge bases request ([commit 46cbdd5](https://github.com/googleapis/google-cloud-dotnet/commit/46cbdd55de24ce6ca9560c16458322c4bbf16ab5))
- Removed OPTIONAL for speech model variant ([commit 853d986](https://github.com/googleapis/google-cloud-dotnet/commit/853d98625a880a54c32b07d87f47924a7d65f84e))

### Documentation improvements

- Added more docs for speech model variant and improved docs format for participant ([commit 853d986](https://github.com/googleapis/google-cloud-dotnet/commit/853d98625a880a54c32b07d87f47924a7d65f84e))

## Version 3.8.0, released 2021-11-18

- [Commit d033f77](https://github.com/googleapis/google-cloud-dotnet/commit/d033f77): feat: support document metadata filter in article suggestion and smart reply model in human agent assistant

## Version 3.7.0, released 2021-11-10

- [Commit 6699f2e](https://github.com/googleapis/google-cloud-dotnet/commit/6699f2e): feat: added support to configure security settings, language code and time zone on conversation profile
- [Commit dd18efd](https://github.com/googleapis/google-cloud-dotnet/commit/dd18efd):
  - docs: clarified meaning of the legacy editions
  - docs: clarified semantic of the streaming APIs

## Version 3.6.0, released 2021-10-12

- [Commit 03f91a3](https://github.com/googleapis/google-cloud-dotnet/commit/03f91a3): docs: recommend AnalyzeContent for future users

## Version 3.5.0, released 2021-09-23

- [Commit 6687459](https://github.com/googleapis/google-cloud-dotnet/commit/6687459): docs: clarified some LRO types
- [Commit ac367e2](https://github.com/googleapis/google-cloud-dotnet/commit/ac367e2): feat: Regenerate all APIs to support self-signed JWTs
- [Commit 0c649d8](https://github.com/googleapis/google-cloud-dotnet/commit/0c649d8): feat: expose `Locations` service to get/list avaliable locations of Dialogflow products; fixed some API annotations

## Version 3.4.0, released 2021-08-10

- [Commit 5dba1ca](https://github.com/googleapis/google-cloud-dotnet/commit/5dba1ca):
  - fix: fix validation result docs
  - feat: add language code to streaming recognition result
  - docs: update environment docs
- [Commit 281077c](https://github.com/googleapis/google-cloud-dotnet/commit/281077c): docs: fix typos

## Version 3.3.0, released 2021-06-22

- [Commit c135978](https://github.com/googleapis/google-cloud-dotnet/commit/c135978): docs: added notes to train agent prior to sending queries fix: added resource reference to agent_version
- [Commit 6567bfc](https://github.com/googleapis/google-cloud-dotnet/commit/6567bfc): feat: added Automated agent reply type and allow cancellation flag for partial response feature.
- [Commit b270512](https://github.com/googleapis/google-cloud-dotnet/commit/b270512): feat: added a field in the query result to indicate whether slot filling is cancelled.
- [Commit fe36e1e](https://github.com/googleapis/google-cloud-dotnet/commit/fe36e1e): feat: added location-aware HTTP path binding for ListIntents
- [Commit b782110](https://github.com/googleapis/google-cloud-dotnet/commit/b782110): fix: removed incorrect resource annotation for UpdateEnvironmentRequest.
- [Commit 88a63a8](https://github.com/googleapis/google-cloud-dotnet/commit/88a63a8):
  - feat: added more Environment RPCs
  - feat: added Versions service
  - feat: added Fulfillment service
  - feat: added TextToSpeechSettings.
  - feat: added location in some resource patterns.

## Version 3.2.0, released 2021-04-29

- [Commit ae565e2](https://github.com/googleapis/google-cloud-dotnet/commit/ae565e2): feat: expose MP3_64_KBPS and MULAW for output audio encodings.
- [Commit a6aa034](https://github.com/googleapis/google-cloud-dotnet/commit/a6aa034):
  - docs: fix link for version and environment in participant doc.
  - fix: Add all missing regional HTTP bindings in DF API.
- [Commit 79f24ea](https://github.com/googleapis/google-cloud-dotnet/commit/79f24ea): feat: Add CCAI API
- [Commit 14e6a6c](https://github.com/googleapis/google-cloud-dotnet/commit/14e6a6c):
  - feat: add additional_bindings to Dialogflow v2 ListIntents API
  - docs: update copyrights and session docs
- [Commit 6e5f4f6](https://github.com/googleapis/google-cloud-dotnet/commit/6e5f4f6): docs: update comments on parameters and validation result.
- [Commit 9900407](https://github.com/googleapis/google-cloud-dotnet/commit/9900407):
  - feat: allowed custom to specify webhook headers through query parameters
  - docs: suggested to always use version for production traffic when calling DetectIntent, mark match_mode in Agent message as deprecated

## Version 3.1.0, released 2020-10-16

- [Commit 079e919](https://github.com/googleapis/google-cloud-dotnet/commit/079e919): docs: fixed link from SentimentAnalysisResult
- [Commit 0790924](https://github.com/googleapis/google-cloud-dotnet/commit/0790924): fix: Add gRPC compatibility constructors
- [Commit 0ca05f5](https://github.com/googleapis/google-cloud-dotnet/commit/0ca05f5): chore: Regenerate all APIs using protoc 3.13 and Grpc.Tools 2.31
- [Commit 0cdabf1](https://github.com/googleapis/google-cloud-dotnet/commit/0cdabf1): docs: wording updates for tiers.
- [Commit ebd848c](https://github.com/googleapis/google-cloud-dotnet/commit/ebd848c): docs: more detailed docs on APIs such as Environment, Intents, Sessions.
- [Commit c552537](https://github.com/googleapis/google-cloud-dotnet/commit/c552537): docs: Regenerate Dialogflow V2 with cleaner docs
- [Commit 6bde7a3](https://github.com/googleapis/google-cloud-dotnet/commit/6bde7a3): docs: Regenerate all APIs with service comments in client documentation
- [Commit 34c92e6](https://github.com/googleapis/google-cloud-dotnet/commit/34c92e6):
  - fix: Update grpc config for retry mechanism.
  - docs: Update ImportAgent/ExportAgent external documentation.
- [Commit f83bdf1](https://github.com/googleapis/google-cloud-dotnet/commit/f83bdf1): fix: Apply timeouts to RPCs without retry
- [Commit 2bac8ab](https://github.com/googleapis/google-cloud-dotnet/commit/2bac8ab): docs: cleaned docs for the Agents service and resource.

## Version 3.0.0, released 2020-06-03

Documentation changes only since 3.0.0-beta02:

- [Commit 4181b4f](https://github.com/googleapis/google-cloud-dotnet/commit/4181b4f): docs: Comment updates only
- [Commit 947a573](https://github.com/googleapis/google-cloud-dotnet/commit/947a573): docs: Regenerate all clients with more explicit documentation
- [Commit b3e7794](https://github.com/googleapis/google-cloud-dotnet/commit/b3e7794): docs: minor comments change.

As noted in the 3.0.0-beta01 history, 3.0.0 is a breaking change compared with 2.0.0 due to resource names being corrected.

## Version 3.0.0-beta02, released 2020-05-05

- [Commit 610cf69](https://github.com/googleapis/google-cloud-dotnet/commit/610cf69):
  - feat: Publish ListEnvironments
  - docs: Clarify WebhookResponse fields
- [Commit f2f7630](https://github.com/googleapis/google-cloud-dotnet/commit/f2f7630): docs: Update comments on Contexts and Sessions resources.

## Version 3.0.0-beta01, released 2020-04-06

- [Commit 5a41fb5](https://github.com/googleapis/google-cloud-dotnet/commit/5a41fb5):
  - Change `parent` field's resource_reference to specify child_type instead of type per client library generation requirement;
  - Change Session with its child resource pattern to support both projects/{project}/agent/sessions/{session} and projects/{project}/agent/environments/{environment}/users/{user}/sessions/{session};
    - Additionally, the location-based pattern has been removed
  - Fix `method_signature`
  - Regular documentation update

This is a breaking change in terms of resource names, which weren't
correctly defined in the API before. We will release a new GA
version once we're satisfied that no further breaking changes will
be required.

## Version 2.0.0, released 2020-03-18

- [Commit a19ee13](https://github.com/googleapis/google-cloud-dotnet/commit/a19ee13):
  - Adds AgentsClient.GetValidationResult RPC with associated types
  - Adds DetectIntentRequest.OutputAudioConfigMask

## Version 2.0.0-beta01, released 2020-02-18

This is the first prerelease targeting GAX v3. Please see the [breaking changes
guide](https://cloud.google.com/dotnet/docs/reference/help/breaking-gax2)
for details of changes to both GAX and code generation.

## Version 1.2.0, released 2019-12-10

- [Commit 532f28b](https://github.com/googleapis/google-cloud-dotnet/commit/532f28b): Multiple new features:
  - Intent.BrowseCarouselCard
  - Intent.MediaContent
  - Intent.TableCard
- [Commit c8a6431](https://github.com/googleapis/google-cloud-dotnet/commit/c8a6431): Added ListSelect.Subtitle

## Version 1.1.0, released 2019-10-02

- [Commit 40e45db](https://github.com/googleapis/google-cloud-dotnet/commit/40e45db): Added WebhookResponse.SessionEntityTypes
- [Commit d314680](https://github.com/googleapis/google-cloud-dotnet/commit/d314680): Added EntityType.EnableFuzzyExtraction
- [Commit 85b53eb](https://github.com/googleapis/google-cloud-dotnet/commit/85b53eb): Added StreamingDetectIntentRequest.SingleUtterence
- [Commit 50658e2](https://github.com/googleapis/google-cloud-dotnet/commit/50658e2): Added Format method to all resource name types

## Version 1.0.0, released 2019-07-10

Initial GA release.
