DKT8iLEm / .baobao02
VPN: 02060102
testclaimui / bRjr323tK3MhRJ

18556412735, Help Desk
UserID =  ruono (Robert/umbrella/Nancy)
ruono@vsp.com
browser.baseUrl
https://github.com/serenity-js/protractor-cucumber-framework-demo
protractor.browser.executeScript
ExecuteScript.sync("document.getElementsByClassName('btn btn-primary')[0].click()"),
ExecuteScript.sync("document.getElementById(‘id’).click()"),
ExecuteScript.sync("arguments[0].click()").withArguments(LoginUi.SIGN_OUT_LINKS),
ExecuteScript.sync("arguments[0].value=''").withArguments(ProcessSuspendedClaimUi.SUSPENDED_CHANGE_AUTHORIZATION_FIELD),
ExecuteScript.sync("console.log('hello world');"),
ExecuteScript.sync("console.log(document.getElementById('claimNumber').value)"),
ExecuteScript.sync("document.getElementById('claimNumber').value=''"),


ExecuteScript.sync("return document.getElementById('patientBirthDate').value"),
Ensure.that(LastScriptExecution.result<string>(), includes(TestData.getAccount(dateTest).validDate_AC1)),


3.Ensure.that(Attribute.of(SearchUI.CLAIM_UI_SEARCH_EXPANSION_PANEL_HEADER).called('aria-expanded'), equals('true')),
// ExecuteScript.sync("console.log(document.getElementsByClassName('mat-tooltip-trigger')[0].getAttribute('mattooltip'))"),

var x = document.getElementsByTagName("H1")[0].getAttribute("class");
test done:
https://jira.vspglobal.com/browse/CSP-29497 


npm run e2e:install
npm run e2e:test-all

ExecuteScript.sync('window.localStorage.clear()'),
Wait.for(Duration.ofSeconds(500)),
static  = Target.the('').located(By.css(''));

Ensure.that(Attribute.of(SearchUi.CLAIM_UI_ADVANCED_SEARCH_EXPANSION_PANEL_HEADER).called('aria-expanded'), equals('true')),


        Wait.upTo(Duration.ofSeconds(30)).until(SpinnerType.OVERLAY_LOADER, not(isPresent())),
        Wait.upTo(Duration.ofSeconds(30)).until(SpinnerType.OVERLAY_LOADER, not(isVisible())),

@default
Scenario Outline: AC

    Given <user> logs in successfully
    And User is on Process Suspended Claim page

    @vsp
    Examples:
        |     user           |
        | basicSearchTest    |


 Then(//, () =>
    actorInTheSpotlight().attemptsTo(
    ));

https://claim-ui-tst.pub.vsp.com/

妈妈：
绝对不舍得我；一定放心不下；相信我的韧性，而非能力。
Sprint1结束了，怅然若失。
// This  will scroll down the page by  1000 pixel vertical		
        js.executeScript("window.scrollBy(0,1000)");

DOM: Get Elements by ID, Tag, Name, Class, CSS Selector
Desk check was done on 2021-06-21 and screenshots was uploaded for the reference. Thanks!
More screenshot could be referenced from the Test Report. Thanks
Desk check was done on 2021-06-21. screenshots was uploaded for the reference.  Result was accepted. Thanks

http://xahlee.info/js/js_get_elements.html
        Enter.theValue('12345671').into(SearchUI.CLAIM_NUMBER_TEXT_BOX),
        ExecuteScript.sync("return document.getElementById('claimNumber').value”),
        Ensure.that(LastScriptExecution.result<string>(), includes('123456731')),