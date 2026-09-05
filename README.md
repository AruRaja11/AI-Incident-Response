Incident
   ↓
Triage Agent
   ↓
 ┌───────────────┬───────────────┐
 ↓               ↓               ↓
Logs Agent    Metrics Agent   Git Agent
 └───────────────┴───────────────┘
                 ↓
          Root Cause Agent
                 ↓
          Risk Assessment
            ↙       ↘
        Low Risk   High Risk
           ↓          ↓
     Auto-fix      Human Approval
           ↓          ↓
       Execute ←─────┘
           ↓
     Verification
           ↓
      Incident Report