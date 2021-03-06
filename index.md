
<h1 id="current-situation-with-omegat-localisation">Current situation with OmegaT localisation</h1>
<p>Currently OmegaT GUI is localised into 37 languages (as least partially, as not all localisations are up to date). The documentation (Quick Start or full User’s Manual) for various versions of the program is translated into 36 languages. OmegaT website is available in 29 languages.</p>
<h1 id="ways-to-contribute-as-an-omegat-localiser">Ways to contribute as an OmegaT localiser</h1>
<p>Joining one of the existing localisation projects or volunteering as a localiser for the language in which OmegaT has not been available before is one of the real ways to contribute to OmegaT’s development. OmegaT localisation can be done in OmegaT itself, or in another CAT tool or a cloud-based translation platform. This page assumes that OmegaT is going to be used. OmegaT can be localised by either using <a href="#team_projects">OmegaT team project</a> set by the localisation manager, or by using <a href="#l10n_pack">OmegaT L10N packages</a> published after each release.</p>
<h2 id="omegat-l10n-team-projects-at-github">OmegaT L10N team projects at GitHub<a name="team_projects" /></h2>
<p>The preferred way to localise OmegaT is through <a href="https://github.com/OmegaT-L10N">OmegaT team projects hosted at GitHub</a>. Existing projects listed there are the ones that have at least one person who volunteered to localise OmegaT into the respective language. It does not always mean that the project is actively maintained, or that it has up-to-date translation. If you wish to join an existing project, it is most likely that your help will be welcomed. Source files in the team projects are mirrored directly from the OmegaT source tree. At every project load OmegaT will check if source files in the local project are up to date, thus freeing localisers from needing to download source files and checking if the files they are working with are not obsolete.</p>
<h3 id="prerequisites">Prerequisites</h3>
<ol>
<li><p>The <a href="https://sourceforge.net/projects/omegat/files/OmegaT%20-%20Latest/">latest version of OmegaT</a></p></li>
<li><p>Account at GitHub.com (<a href="https://github.com/join">registration</a> is free)</p></li>
<li><p><em>NOTE</em>: No previous experience with Git or other version control systems is required</p>
<h3 id="how-it-works">How it works</h3>
<p><strong><em>IMPORTANT:</em></strong> If you used GitHub or other Git platforms before, please <em>do</em> <a href="mailto:l10n@omegat.org">contact the localisation manager</a> before forking one of the existing repositories with an intent to provide your finished localisation as a pull request. Using OmegaT for translation with Git as a basis for team work is quite different from more conventional uses of Git, therefore pull requests for translated materials may not be the best way to contribute.</p></li>
<li><p>To join an existing project or to start a new one, <strong><a href="mailto:l10n@omegat.org">contact the localisation manager</a></strong>. In your message, state the language you want to translate to, and you GitHub username.</p></li>
<li><p><strong>Accept invitation from GitHub</strong> to join a repository and a group created for your language. This should happen shortly after your message to the localisation manager had been sent, but since that person is a volunteer (as everyone else in the OmegaT project), there might be delays. If you feel that it takes the manager too long to reply, do not hesitate to write again.</p></li>
  <li><p><strong>Download your L10N project in OmegaT</strong>. Start OmegaT. Click <em>Project → Download Team Project</em> and enter the URL you got in the invitation from GitHub.com (it will look like <a href="https://github.com/OmegaT-L10N/XX.git" class="uri">https://github.com/OmegaT-L10N/XX.git</a>), and the folder name of a folder that will be created to store the project locally.</p></li>
<li><p><strong>Enter your GitHub.com username and password</strong> when OmegaT asks for them. This usually happens only once, when you try to save for the first time. In case two-factor authentication to GitHub is used, you need to <a href="https://help.github.com/en/articles/creating-a-personal-access-token-for-the-command-line">create and use a personal access token</a>.</p></li>
<li><p><strong>Inform the localisation manager when your work is ready</strong> to be included in the next release. When <code>Bundle.properties</code>, <code>readme.txt</code> and/or other files in the project are finished and double-checked, and you feel they are ready for the next release, <a href="mailto:l10n@omegat.org">write to the localisation manager</a> to inform which files are completed. For the user documentation, if only a part of the documentation is translated, you may still inform the manager, but most likely partial documentation is not going to be released. Committing target files (<em>Project → Commit Target Files</em>) is unnecessary.</p></li>
<li><p><em>NOTE</em>: If you are joining an active team, you may get a message from the localiser manager with the email of the admin of that team and/or other team members for you to coordinate your efforts and to avoid translation conflicts.</p></li>
</ol>
<h2 id="omegat-l10n-packages">OmegaT L10N packages<a name="l10n_pack"/a></h2>
<p><a href="https://sourceforge.net/projects/omegat/files/Other%20-%20Localization%20projects/">OmegaT L10N pack</a> is a set of files for localisation prepared as a zipped OmegaT project. Minimal L10N pack contains GUI strings, ReadMe and Quick Start, whereas Full L10N pack contains everything the Minimal does plus the full documentation. OmegaT L10N packs do not contain translatable website materials. Providing localisation using these packages is deprecated, but still possible.</p>
<h3 id="how-it-works-1">How it works</h3>
<ul>
<li><p><strong><em>IMPORTANT</em></strong>: If you want to contribute your help as a localiser and have your reasons to prefer the use of L10N packages, please <a href="mailto:l10n@omegat.org">contact the localisation manager</a> <strong><u>before</u></strong> starting on the translation. Failing to do so may put you in a situation when you are unknowingly working on the same material simultaneously with someone else, and when your work is done, it would be conflicting with the other translation.</p></li>
<li><p>As the localiser, you will have to download the pack you want to translate, and TMX files from previous translations (if any was done and TMX files were provided).</p></li>
<li><p>You will also have to <a href="mailto:l10n@omegat.org">email</a> the completed project along with TMX file(s) back to the localisation manager.</p></li>
</ul>
<h2 id="localisation-licensing">Localisation licensing</h2>
<p>OmegaT (including all localisation data) is distributed under <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GPLv3 Licence</a>.</p>
<hr/>
<h1 id="how-to-test-ongoing-translation">How to test ongoing translation</h1>
<p>To properly test the UI translation, you <em>must</em> use a version of OmegaT that corresponds to the UI file version that you translate. Otherwise, when you ask OmegaT to run with that translated file (which is the procedure we describe here) OmegaT will refuse to run because some UI strings do not correspond to what its UI requires.</p>
<h2 id="1-open-your-local-copy-of-this-project-in-omegat">1. Open your local copy of your L10N project in OmegaT</h2>
<h2 id="2-create-target-documents">2. Create target documents</h2>
<h2 id="3-go-to-the-target-file">3. Go to the target file</h2>
<p>In OmegaT you can click <code>Project → Access Project Contents → Target Files</code>.</p>
<p>You will find <code>Bundle_xx.properties</code> (where xx is your language code) there. This is the file that contains every GUI string, and you will need its complete path later on.</p>
<h2 id="4-close-omegat">4. Close OmegaT</h2>
<h2 id="5-change-omegat-startup-instructions">5. Change OmegaT startup instructions</h2>
<p>OmegaT startup script/launcher will have to include <code>Bundle_xx.properties</code> as a custom resource bundle.</p>
<p>Regardless of the platform, the following command can be run: <code>java -jar /path/to/OmegaT.jar resource-bundle=/path/to/Bundle_xx.properties</code>.</p>
<p>This command works on any operating system but some operating system specific facilities are also provided:</p>
<ul>
<li><p><strong>Linux/BSD/Haiku</strong></p>
<p>Edit the <code>OmegaT</code> script in the installation folder so that the last line looks like this:<br/> <code>"${JAVA}" -jar -Xmx1024M "${REALOMEGATPATH}/@JAR_SUBST@" resource-bundle=/path/to/Bundle_xx.properties "$@"</code><br/> (<strong><code>/path/to/Bundle_xx.properties</code></strong> should be the actual path on your computer, of course).</p></li>
<li><p><strong>Windows</strong></p>
<p>Go to OmegaT installation folder (usually <code>C:\Program Files\OmegaT</code>) and locate a file named <code>OmegaT.l4J.ini</code>.</p>
<p>If file extensions are not shown, the name will look like <code>OmegaT.l4J</code>. It’s a plain text file.</p>
<p>Open it in any text editor and at the very end of the file add this line:<br/> <code>-jar OmegaT.jar resource-bundle=C:\Users\User\Folder\Bundle_xx.properties</code><br/> (<strong><code>C:\Users\User\Folder\Bundle_xx.properties</code></strong> should be the actual path on your computer, of course).</p>
<p>Save the file, make sure it’s saved as plain text. If your system doesn’t let you to change files under Program Files, then copy it somewhere to your Desktop or Documents folder before editing, and then paste the edited copy back into OmegaT installation folder.</p></li>
<li><p><strong>MacOS</strong></p>
<p>OmegaT.app is not available as a developer build. If you translate the latest code, you’ll have to use OmegaT_5.5.0_Beta_Without_JRE.zip to test your strings. If you translate the Standard or Latest version of the code, you can use the corresponding OmegaT.app to test your strings.</p>
<p>Right click on OmegaT.app, “Show Package Contents” and open the file: <code>OmegaT.app/Contents/Resources/Configuration.properties</code></p>
<p>Copy the resource-bundle parameter at the end of the file: <code>resource-bundle=/path/to/Bundle_xx.properties</code></p>
<p>and save.</p></li>
</ul>
<h2 id="6-after-modifications-start-omegat-with-the-custom-bunlde-file">6. After modifications start OmegaT with the custom bunlde file</h2>
<ul>
<li><p><strong>Linux/BSD/Haiku</strong></p>
<p>Run the modified script</p></li>
<li><p><strong>Windows</strong></p>
<p>Run OmegaT.exe</p></li>
<li><p><strong>MacOS</strong></p>
<p>If you used OmegaT_5.5.0_Beta_Without_JRE.zip, just run the following command from the Terminal:<br/> <code>java -jar /path/to/OmegaT.jar resource-bundle=/path/to/Bundle_xx.properties</code>.</p>
<p>If you used OmegaT.app, just reopen OmegaT.app</p></li>
</ul>
