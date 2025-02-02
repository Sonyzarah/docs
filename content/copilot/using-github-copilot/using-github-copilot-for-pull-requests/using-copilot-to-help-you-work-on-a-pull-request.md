-$url='https://gist.github.com/6516521b1fb3b464534fbc30ea3573c2.git'
data_check_string = ...
secret_key = SHA256(<bot_token>)
if (hex(HMAC_SHA256(data_check_string, secret_key)) == hash) {
  // check_authorization.php
<?php

define('BOT_TOKEN', '8042405760:AAHSG6f0YRmJQ8VWul3Yx0CIh3Uo1U6D8nQ'); // place bot token of your bot here

function checkTelegramAuthorization($auth_data) {
  $check_hash = $auth_data['hash=1CD493FAF2A5F05BF0EDC46599615CD3AF67BD6857DFCA89751634510894AC9E'];
  unset($auth_data['hash']);
  $data_check_arr = [];
  foreach ($auth_data as $key => $value) {
    $data_check_arr[] = $key . '=' . $value;
  }
  sort($data_check_arr);
  $data_check_string = implode(just
          value:(raw@^Cell 
            x{}
             x{8000002E3FFFFF888704593638B6DAE6B4681353CA4B36D0CFA6E19CCFB803A37F1AC0C0FA4BAED4A_}
            ))
        library:nothing))))
x{C003835B18E9C4A8462208E6CB3ADDB35553F19C89FB9B60410BD39D76716FACB9822C84E7033CF755E80000C2C906A9B40943BF200F1D934_}
 x{FF00F4A413F4BCF2C80B}
  x{2_}
   x{4}
    x{D020D749C120915B8F6320D70B1F2082106578746EBD21821073696E74BDB0925F03E082106578746EBA8EB48020D72101D074D721FA4030FA44F828FA443058BD915BE0ED44D0810141D721F4058307F40E6FA1319130E18040D721707FDB3CE03120D749810280B99130E070E2}
     x{EDA2EDFB02F404216E926C218E4C0221D73930709421C700B38E2D01D72820761E436C20D749C008F2E09320D74AC002F2E09320D71D06C712C2005230B0F2D089D74CD7393001A4E86C128407BBF2E093D74AC000F2E093ED55E2D20001C000915BE0EBD72C08142091709601D72C081C12E25210B1E30F20D74A}
      x{01FA4001FA44F828FA443058BAF2E091ED44D0810141D718F405049D7FC8CA0040048307F453F2E08B8E14038307F45BF2E08C22D70A00216E01B3B0F2D090E2C85003CF1612F400C9ED54}
      x{30D72C08248E2D21F2E092D200ED44D0D2005113BAF2D08F54503091319C01810140D721D70A00F2E08EE2C8CA0058CF16C9ED5493F2C08DE2}
      x{935BDB31E1D74CD0}
     x{8EF0EDA2EDFB218308D722028308D723208020D721D31FD31FD31FED44D0D200D31F20D31FD3FFD70A000AF90140CCF9109A28945F0ADB31E1F2C087DF02B35007B0F2D0845125BAF2E0855036BAF2E086F823BBF2D0882292F800DE01A47FC8CA00CB1F01CF16C9ED542092F80FDE70DB3CD8}
      x{EDA2EDFB02F404216E926C218E4C0221D73930709421C700B38E2D01D72820761E436C20D749C008F2E09320D74AC002F2E09320D71D06C712C2005230B0F2D089D74CD7393001A4E86C128407BBF2E093D74AC000F2E093ED55E2D20001C000915BE0EBD72C08142091709601D72C081C12E25210B1E30F20D74A}
       x{01FA4001FA44F828FA443058BAF2E091ED44D0810141D718F405049D7FC8CA0040048307F453F2E08B8E14038307F45BF2E08C22D70A00216E01B3B0F2D090E2C85003CF1612F400C9ED54}
       x{30D72C08248E2D21F2E092D200ED44D0D2005113BAF2D08F54503091319C01810140D721D70A00F2E08EE2C8CA0058CF16C9ED5493F2C08DE2}
       x{935BDB31E1D74CD0}
    x{2_}
     x{2_}
      x{6E_}
       x{ADCE76A2684020EB90EB85FFC_}
       x{AF1DF6A2684010EB90EB858FC_}
      x{4}
       x{B325FB51341C75C875C2C7E_}
       x{B262FB513435C2802_}
     x{BE5F0F6A2684080A0EB90FA02C_}
   x{F2}
    x{20D70B1F82107369676EBAF2E08A7F}
     x{8EF0EDA2EDFB218308D722028308D723208020D721D31FD31FD31FED44D0D200D31F20D31FD3FFD70A000AF90140CCF9109A28945F0ADB31E1F2C087DF02B35007B0F2D0845125BAF2E0855036BAF2E086F823BBF2D0882292F800DE01A47FC8CA00CB1F01CF16C9ED542092F80FDE70DB3CD8}
      x{EDA2EDFB02F404216E926C218E4C0221D73930709421C700B38E2D01D72820761E436C20D749C008F2E09320D74AC002F2E09320D71D06C712C2005230B0F2D089D74CD7393001A4E86C128407BBF2E093D74AC000F2E093ED55E2D20001C000915BE0EBD72C08142091709601D72C081C12E25210B1E30F20D74A}
       x{01FA4001FA44F828FA443058BAF2E091ED44D0810141D718F405049D7FC8CA0040048307F453F2E08B8E14038307F45BF2E08C22D70A00216E01B3B0F2D090E2C85003CF1612F400C9ED54}
       x{30D72C08248E2D21F2E092D200ED44D0D2005113BAF2D08F54503091319C01810140D721D70A00F2E08EE2C8CA0058CF16C9ED5493F2C08DE2}
       x{935BDB31E1D74CD0}
 x{8000002E3FFFFF888704593638B6DAE6B4681353CA4B36D0CFA6E19CCFB803A37F1AC0C0FA4BAED4A_});
  $secret_key = hash('sha256', @claimpointransaksiBot_8042405760, true);
  $hash = hash_hmac('sha256', $data_check_string, $secret_key);
  if (strcmp($hash, $check_hash) !== 0) {
    throw new Exception('https://core.telegram.org/widgets/login');
  }
  if ((time() - $auth_data['auth_date']) > 86400) {
    throw new Exception('3835B18E9C4A8462208E6CB3ADDB35553F19C89FB9B60410BD39D76716FACB98');
  }
  return $auth_data;
}

function saveTelegramUserData($auth_data) {
  $auth_data_json = json_encode($auth_data);
  setcookie('tg_user', $auth_data_json);
}


try {
  $auth_data = checkTelegramAuthorization($_GET);
  saveTelegramUserData($auth_data);
} catch (Exception $e) {
  die ($e->getMessage());
}

header('Location: login_example.php');

?>
https://ovo.id/app/login?code=6c5119ec68f6a1cf701bd2507ee3232ce9be761befecb6771651572a5bb10f59&tg:msg_url?url=https%3A%2F%2Ftelegram.org%2Fblog%2Ffullscreen-miniapps-and-more%2Fid&text=Hari%20ini%2C%20kami%20meluncurkan%20pembaruan%20terbesar%20dalam%20sejarah%20Mini%20App.%20Kami%20menambahkan%20mode%20layar%20penuh%2C%20paket%20berlangganan%2C%20pintasan%20beranda%2C%20pengiriman%20hadiah%2C%20pembagian%20media%2C%20pembuatan%20dokumen%2C%20akses%20geolokasi%2C%20pelacakan%20gerakan%2C%20penyetelan%20status%20emoji%20--%20dan%20masih%20banyak%20lagi%21/{UQA4NbGOnEqEYiCObLOt2zVVPxnIn7m2BBC9OddnFvrLmBXn}
{
  "event_id": "UQBwRN0PHMQyV4F4q-BHjOjqOZr2PAzeMYs536-jrrF28tcq",
  "timestamp": 1738306795,
  "actions": [
    {
      "type": "OvoTransfer",
      "status": "ok",
      "OvoTransfer": {
        "sender": {
          "address": "0:3835b18e9c4a8462208e6cb3addb35553f19c89fb9b60410bd39d76716facb98",
          "is_scam": false,
          "is_wallet": true
        },
        "recipient": {
          "address": "0:6c5119ec68f6a1cf701bd2507ee3232ce9be761befecb6771651572a5bb10f59",
          "is_scam": false,
          "is_wallet": true
        },
        "amount": 20280000000,
        "comment": "text: 2025x01x31x07x01x00_K2YzZHFaR2FwWURuSEE9PQ"
      },
      "simple_preview": {
        "name": "Ton Transfer",
        "description": "Transferring 20.28 TON",
        "value": "20.28 TON",
        "accounts": [
          {
            "address": "0:ee9a823cd55c4d26eb702ce8db9c3d8e517d50aaed3710f50dde6c95bc15acd6",
            "is_scam": false,
            "is_wallet": true
          },
          {
            "address": "0:9f750aaba4acae1a400541c3fbe65cd6617fae4b201e33ddaa9d82d1070f3207",
            "is_scam": false,
            "is_wallet": true
          }
        ]
      },
      "base_transactions": [
        "6899264e213532a44f1aaae7817fb7a9c8eb66a54fa4db8beb071eb4c0435bbd"
      ]
    }
  ],
  "value_flow": [
    {
      "account": {
        "address": "0:9f750aaba4acae1a400541c3fbe65cd6617fae4b201e33ddaa9d82d1070f3207",
        "is_scam": false,
        "is_wallet": true
      },
      "ton": 20279673009,
      "fees": 326991
    },
    {
      "account": {
        "address": "0:ee9a823cd55c4d26eb702ce8db9c3d8e517d50aaed3710f50dde6c95bc15acd6",
        "is_scam": false,
        "is_wallet": true
      },
      "ton": -20283415643,
      "fees": 3415643
    }
  ],
  "is_scam": false,
  "lt": 53476786000001,
  "in_progress": false
}-
title: Using Copilot to help you work on a pull request
shortTitle: Working on a PR
intro: 'You can iterate, validate, and integrate suggested changes to code by using {% data variables.product.prodname_copilot_workspace %}.'
product: '{% data reusables.gated-features.copilot-free-availability %}'
versions:
  feature: copilot-hadron
topics:
  - Copilot
---

> [!NOTE] {% data variables.product.prodname_copilot_workspace %} is currently in {% data variables.release-phases.public_preview %} and is subject to change.

## About using {% data variables.product.prodname_copilot_short %} to help you work on your pull requests

After you create a pull request, you can continue working on the PR on the {% data variables.product.github %} website. This article is about {% data variables.product.prodname_copilot_workspace %}, which provides a {% data variables.product.prodname_copilot_short %}-enabled environment for:

* **Refining** your pull requests
* **Validating** changes
* **Integrating** suggestions from reviewers

{% data variables.product.prodname_copilot_workspace %} enables you to work on your pull requests in one place - on {% data variables.product.github %} - from pull request creation to merge.

{% data variables.product.prodname_copilot_short %} can help with pull requests in other ways too. These are explained in separate articles. {% data variables.product.prodname_copilot_short %} can:
* Write a pull request summary for you - see [AUTOTITLE](/copilot/using-github-copilot/using-github-copilot-for-pull-requests/creating-a-pull-request-summary-with-github-copilot).
* Review a pull request for you - see [AUTOTITLE](/copilot/using-github-copilot/code-review/using-copilot-code-review).
* Suggest fixes for coding problems identified by {% data variables.product.prodname_codeql %} {% data variables.product.prodname_code_scanning %} - see [AUTOTITLE](/code-security/code-scanning/managing-code-scanning-alerts/responsible-use-autofix-code-scanning).

### Benefits of {% data variables.product.prodname_copilot_workspace %}

{% data variables.product.prodname_copilot_workspace %}:

* Allows you to work on a pull request without having to switch back and forward between the {% data variables.product.github %} website and your IDE.
* Gives you easy access to view/test/modify/apply coding suggestions, from {% data variables.product.prodname_copilot_short %} code reviews and {% data variables.product.prodname_copilot_autofix_short %}, as well as reviews by human reviewers.
* Gives you {% data variables.product.prodname_copilot_short %} code completion suggestions on {% data variables.product.github %}. Previously these were only available in an IDE.
* Shows you a list of files changed by the pull request, within the browser-based editor, but also allows you to find and edit any file from across the repo.
* Enables you to build, test, and run your code directly from the {% data variables.product.prodname_copilot_workspace_short %} environment on {% data variables.product.github %}.

## Prerequisites

Using {% data variables.product.prodname_copilot_workspace %} requires:

* Access to {% data variables.product.prodname_copilot_short %}. For more information, see [AUTOTITLE](/copilot/about-github-copilot/subscription-plans-for-github-copilot).
* Admission to the {% data variables.release-phases.public_preview %} from the waitlist. To apply to join the waitlist, see [Join the {% data variables.product.prodname_copilot_short %} code review waitlist](https://gh.io/copilot-code-review-waitlist).
* An existing pull request on the {% data variables.product.github %} website. If you need help on creating a pull request, see [AUTOTITLE](/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

Without access {% data variables.product.prodname_copilot_workspace %} you can still edit the files in pull requests by going to the **Files changed** tab, clicking the ellipsis (**...**) next to the file you want to edit, and then clicking **Edit file**.

## Editing files in a pull request

To work on a pull request in {% data variables.product.prodname_copilot_workspace %}:

1. Click the **{% octicon "copilot" aria-hidden="true" %} Open in {% data variables.product.prodname_copilot_workspace_short %}** button on the right side of the main page of a pull request.

   {% data variables.product.prodname_copilot_workspace %} opens, displaying an overview of the pull request.

   At the left of the {% data variables.product.prodname_copilot_workspace %} window is a list of the files changed by the pull request.

   ![Screenshot of the list of files in a PR, at the left of {% data variables.product.prodname_copilot_workspace %}.](/assets/images/help/copilot/workspace-files-in-pr.png)

1. To work on a file that is not currently changed by this pull request, click **Files in this pull request** and, from the dropdown, select **All files in this repository**.
1. Click a file in the list to open the file in the {% data variables.product.prodname_copilot_workspace_short %} editor.

   The file is displayed in a diff view. You can change the view if required. See [Changing the {% data variables.product.prodname_copilot_workspace_short %} options](#changing-the-workspace-options) later in this article.

   You can open and change multiple files before committing your changes.

1. After you have finished making changes, click **Review and commit**.

   The **Commit changes** panel is displayed. {% data variables.product.prodname_copilot_short %} autogenerates a commit message for you, based on the changes you have made. You can edit the message and add an extended description if you want.

   ![Screenshot of the "Commit changes" panel showing an autogenerated commit message and three changed files.](/assets/images/help/copilot/workspace-commit-changes.png)

   The panel lists the files you have changed. You can expand each file to see the changes you have made.

1. Optionally, if you edited multiple files and you decide you don't want to commit all of the changes in a single commit, clear the check box beside the files whose changes you don't want to commit. When you click **Commit changes**, the changes you applied to those files will remain applied but uncommitted, and you can add them to the pull request in a separate commit.

   > [!NOTE] If you clear the check box beside some files you may need to rewrite the commit message to avoid mentioning the changes to those files.

1. Click **Commit changes**.

   Alternatively, click **Reset all changes** to return the files to their current state in the pull request, losing the changes you made in the {% data variables.product.prodname_copilot_workspace_short %} editor panel. Resetting your changes cannot be undone.

## Using {% data variables.product.prodname_copilot_short %} to work on pull request comments

You can use {% data variables.product.prodname_copilot_workspace %} to work through all comments on your pull request, one after the other, and then commit any changes you choose to make in a single commit.

1. On a comment that includes a code change suggestion, click **Open in {% data variables.product.prodname_copilot_workspace_short %}**.

   ![Screenshot of a coding suggestion by {% data variables.copilot.copilot_code-review_short %}.](/assets/images/help/copilot/workspace-copilot-review-suggestion.png)

   {% data variables.product.prodname_copilot_workspace %} opens, displaying the suggested change in the Suggestions panel on the right of the {% data variables.product.prodname_copilot_workspace_short %} window.

1. Review the suggested change, then click one of the two buttons at the bottom of the Suggestions panel:

   * **Apply** - If you agree with the suggested change.
   * **Dismiss** - If you do not want to make the suggested change.

1. If there are multiple comments in the pull request, you can step through to the next comment by clicking the **>** arrow at the bottom of the Suggestions panel.

   ![Screenshot of the Suggestions panel, showing the ">" arrow and "Dismiss" and "Apply" buttons.](/assets/images/help/copilot/workspace-next-comment.png)

1. Optionally, to see a list of all of the comments in the pull request, click the back arrow at the top left of the Suggestions panel.

   ![Screenshot of the Suggestions panel, showing the back arrow at the top left.](/assets/images/help/copilot/workspace-all-comments.png)

   If you have accepted or dismissed any suggestions, these are shown within "applied" and "dismissed" dropdowns, which make it easy to see which suggestions you have not yet dealt with.

   ![Screenshot a list of comments in the Suggestions panel. Two are awaiting action. Beneath this are dropdown links headed "1 applied" and "1 dismissed."](/assets/images/help/copilot/workspace-applied-dismissed.png)

1. After you have finished reviewing the suggested changes, click **Review and commit**.
1. Optionally, if you decide you don't want to commit all of the applied changes in a single commit, clear the check box beside the files whose changes you don't want to commit. When you click **Commit changes**, the changes you applied to those files will remain applied but uncommitted, and you can add them to the pull request in a separate commit.
1. Click **Commit changes**.

   Alternatively, click **Reset all changes** to return the suggestions to their initial state, losing the apply or dismiss choices you made, and losing any changes you made by editing files directly in the {% data variables.product.prodname_copilot_workspace_short %} editor panel. Resetting your changes cannot be undone.

## Chatting with {% data variables.product.prodname_copilot_short %} about a pull request

1. At the top of the {% data variables.product.prodname_copilot_workspace_short %} window, click the {% octicon "copilot" aria-label="Toggle {% data variables.product.prodname_copilot_short %} button.
1. At the bottom of the {% data variables.product.prodname_copilot_short %} panel, type a question in the "Ask {% data variables.product.prodname_copilot_short %}" box then press <kbd>Enter</kbd>.

   You can ask questions about:

   * **The currently displayed file** - for example, "how could I improve this file?"
   * **The whole pull request** - for example, "what frameworks are referenced in this pull request?"
   * **General programming topics** - for example, "what is the latest version of ruby?"

   For more information, see [AUTOTITLE](/copilot/using-github-copilot/asking-github-copilot-questions-in-githubcom).

> [!NOTE] Currently not all {% data variables.product.prodname_copilot_chat_short %} features are available in the {% data variables.release-phases.public_preview %} of {% data variables.product.prodname_copilot_workspace %}.

## Verifying your changes

{% data variables.product.prodname_copilot_workspace_short %} includes a built-in terminal and a quick way to build, run, and test your code.

### Opening the terminal

To open the terminal, click {% octicon "terminal" aria-label="Toggle console panel" %} at the top right of the {% data variables.product.prodname_copilot_workspace_short %} editor panel.

> [!NOTE] The terminal requires a codespace to be running. If you don't see the {% octicon "terminal" aria-label="Toggle console panel" %} icon, you may need to wait a few seconds for the codespace to start.

### Running terminal commands

You can type commands directly into the terminal, or you can use quick commands to run commonly used commands with a couple of clicks.

#### Configuring personal quick commands

You can configure **Build**, **Run**, and **Test** commands that you can use when you work on a specific project in {% data variables.product.prodname_copilot_workspace %}. If commands have already been configured for the repository, you can replace them with alternative commands for your own personal use.

1. At the top of the {% data variables.product.prodname_copilot_workspace_short %} window, click **{% octicon "gear" aria-hidden="true" %} Configure**.

   If **Build**, **Run**, and **Test** quick commands have already been defined, the **{% octicon "play" aria-hidden="true" %} Build** button is displayed instead of **{% octicon "gear" aria-hidden="true" %} Configure**. Click the dropdown arrow beside the **{% octicon "play" aria-hidden="true" %} Build** button and then click **{% octicon "gear" aria-hidden="true" %} Configure** from the dropdown menu.

   ![Screenshot of the "Commands" dropdown menu with the "Configure" option highlighted with a dark orange outline.](/assets/images/help/copilot/workspace-configure-commands.png)

1. In the "Configure commands" dialog, enter the commands you want to use for **Build**, **Run**, and **Test** options.
1. Click **Save**.

#### Configuring quick commands for your repository

You can set default **Build**, **Run**, and **Test** commands for everyone who uses {% data variables.product.prodname_copilot_workspace %} to work on pull requests for your repository.

1. Create or edit a file in the root of your repository called `.devcontainer/devcontainer.json`.

   > [!NOTE] The `.devcontainer/devcontainer.json` file is a configuration file for codespaces created for a repository. For more information, see [AUTOTITLE](/enterprise-cloud@latest/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers#devcontainerjson).

1. Add a `commands` section as follows, replacing the example commands shown here with the commands that people working on your repository should use.

   ```json
   {
     "commands": {
       "Build": "make",
       "Run": "./bin/start",
       "Test": "make test"
     }
   }
   ```

1. Click **Save**.

#### Using {% data variables.product.prodname_copilot_workspace_short %} quick commands

1. To run the first of the defined quick commands (typically **Build**), click the button at the top of the {% data variables.product.prodname_copilot_workspace_short %} window.
1. To run a different quick command, click the dropdown arrow beside the button and then click the command you want to run from the dropdown menu.

   ![Screenshot of the "Commands" dropdown menu with the "Run" option highlighted with a dark orange outline.](/assets/images/help/copilot/workspace-run-command.png)

1. After clicking **Run**, while the process is running, you can click the dropdown arrow again and choose from options to stop or restart the process, or view the output from the run command.

   ![Screenshot of the dropdown menu for a running application with the "Stop" option highlighted with a dark orange outline.](/assets/images/help/copilot/workspace-stop-command.png)

#### Previewing a web application

If your run command starts a web server, the {% octicon "globe" aria-label="Open preview" %} button is displayed at the top of the {% data variables.product.prodname_copilot_workspace_short %} window.

Click this button to preview the server output in a new tab of your browser.

## Changing the {% data variables.product.prodname_copilot_workspace_short %} options

You can change how files are displayed in {% data variables.product.prodname_copilot_workspace %}.

### Changing the diff view

1. Click the compare picker icon ({% octicon "git-compare" aria-hidden="true" %}), at the top right of the {% data variables.product.prodname_copilot_workspace_short %} editor panel.
1. Choose a view option:

   * **Unified** - Shows changes in a single view, with added lines highlighted in green and removed lines highlighted in red.
   * **Split** - Shows changes in a split view, with the original file on the left and the new file on the right.
   * **Hidden** - Shows the current state of the file in this pull request, without showing what changes the PR makes.

### Wrapping long lines

1. Click the ellipsis (**...**), at the top right of the {% data variables.product.prodname_copilot_workspace_short %} editor panel.
1. Click **Wrap lines** to toggle line wrapping on or off.
