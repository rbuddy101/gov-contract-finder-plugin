# Gov Contract Finder

Find federal opportunities, research public contractor facts, read original solicitation documents, and save opportunities and searches to your connected workspace.

## Connect and use

A Gov Contract Finder account is required for every tool. A free account can connect; existing workspace save allowances apply. Sign in through the host's OAuth connection screen, choose your workspace and review the read/save permissions. Never put a password or access token in chat.

- “Find janitorial opportunities in Arizona.”
- “What do the documents for this opportunity require us to submit?”
- “Save this opportunity and its search, then show my saved research.”

Connection: https://search.govcontractfinder.com/mcp

[Setup and coverage](https://govcontractfinder.com/claude) · [Support](https://govcontractfinder.com/support) · [Privacy](https://govcontractfinder.com/privacy-policy#ai-connections) · [Terms](https://govcontractfinder.com/terms-and-conditions)

## What the plugin does

The package contains a remote MCP connection and a research skill. It installs no executables, dependencies, hooks or background jobs. Tool requests send the requested search criteria, public notice or company identifiers, pagination, and user-chosen saved-search names to Gov Contract Finder. The service verifies your account and workspace permission and returns public research or your saved research. Saves happen only when requested and do not enable alerts, send messages or synchronize calendars. Contractor research is read-only. Internal CRM records and contact enrichment are not available.

For document questions, the skill asks the host to download and read relevant original public SAM.gov files with its native document tools. These downloads go to SAM.gov and its attachment storage, outside the declared Gov Contract Finder connection. The original hosts receive normal download requests. Document content is treated as source material, never instructions. Availability and file support depend on the source and host; the answer identifies unread files and cites the files it actually read. A link alone is not a document analysis.

## Privacy and control

The connection processes only the fields needed for the requested tool call; it does not request the full chat history or local files. The host receives the requested results under its own policies. Saved research stays in your selected workspace until removed through the website or the applicable account/workspace deletion process. Shared workspace records may remain for other members. Connection records and retention are described in the linked privacy policy.

Revoke access in [Connected apps](https://govcontractfinder.com/dashboard/integrations). Revocation stops future access without deleting saved work or prior chat messages. [Request account deletion](https://govcontractfinder.com/delete-account) or contact team@govcontractfinder.com for privacy requests and connection support.

## License

See LICENSE for the package's use and distribution terms. The license covers this package only, not the hosted server, the private monorepo, or third-party documents.
