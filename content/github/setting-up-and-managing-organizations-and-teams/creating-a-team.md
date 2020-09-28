---
title: Creating a team
intro: You can create independent or nested teams to manage repository permissions and mentions for groups of people.
redirect_from:
  - /articles/creating-a-team-early-access-program/
  - /articles/creating-a-team
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

Only organization owners and maintainers of a parent team can create a new child team under a parent. Owners can also restrict creation permissions for all teams in an organization. For more information, see "[Setting team creation permissions in your organization](/articles/setting-team-creation-permissions-in-your-organization)."

{{ site.data.reusables.organizations.team-synchronization }}

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.new_team }}
{{ site.data.reusables.organizations.team_name }}
{{ site.data.reusables.organizations.team_description }}
{{ site.data.reusables.organizations.create-team-choose-parent }}
{% if currentVersion == "free-pro-team@latest" %}
1. Optionally, if your organization or enterprise account uses team synchronization, to connect an identity provider group to your team, use the "Identity Provider Groups" drop-down menu, and select up to 5 identity provider groups. For more information, see "[Synchronizing a team with an identity provider group](/github/setting-up-and-managing-organizations-and-teams/synchronizing-a-team-with-an-identity-provider-group)."
    ![Drop-down menu to choose identity provider groups](/assets/images/help/teams/choose-an-idp-group.png)
{% endif %}
{{ site.data.reusables.organizations.team_visibility }}
{{ site.data.reusables.organizations.create_team }}
9. Optionally, [give the team access to organization repositories](/articles/managing-team-access-to-an-organization-repository).

### Further reading

- "[About teams](/articles/about-teams)"
- "[Changing team visibility](/articles/changing-team-visibility)"
- "[Moving a team in your organization's hierarchy](/articles/moving-a-team-in-your-organization-s-hierarchy)"