# Macro Doctor Documentation

## Install
A Confluence admin installs Macro Doctor from the Atlassian Marketplace. The app asks for two read-only permissions: view spaces and view pages.

## Scan a space
1. In Confluence, open **Apps** and choose **Macro Doctor**.
2. Choose a space. You can type to filter the list.
3. Select **Scan space**. The button shows how many pages have been read.
4. Review the results.

You only see spaces and pages you are allowed to view. To scan restricted pages, ask someone with access to run the scan.

## Read the results
**Summary** – how many pages need attention, and a count for each kind of problem.

**Issues** – one row per problem, with a link to the page.

| Problem | Severity | What to do |
|---|---|---|
| Unmigrated wiki markup | broken | Rewrite the block in the editor. |
| Macro not available in Cloud | broken | Replace it with a Cloud feature or a Marketplace app. |
| Macro to review | review | Check whether an installed app provides this macro. If not, it shows as an unknown macro. |
| Nested bodied macro | review | Open the page in the editor and check that it renders. Flatten the nesting if it does not. |
| Visibility rule with old user or group name | review | Update the rule to use Cloud users or groups. |
| Old user reference | broken | Re-enter the mention with the Cloud user. |
| Old page URL | review | Replace the link with the Cloud page link. |

**Macro inventory** – every macro name in the space, with the number of uses and pages.

## Limits
- Results are heuristics. Macro Doctor may flag macros that work because an app provides them, and it cannot tell whether a macro renders correctly.
- Macro Doctor does not fix pages.
- Results are not saved. Run the scan again to refresh them.

## Support
poiu1579@gmail.com
