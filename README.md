<p data-renderer-start-pos="525" style='margin: 0.75rem 0px 0px; padding: 0px; font-size: 16px; line-height: 1.714; font-weight: 400; letter-spacing: -0.005em; color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans", Ubuntu, "Droid Sans", "Helvetica Neue", sans-serif; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: pre-wrap; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgba(255, 255, 255, 0.6); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;'><strong data-renderer-mark="true">Databricks &ndash; UAC Integration</strong>&nbsp;</p>
<p data-renderer-start-pos="556" style='margin: 0.75rem 0px 0px; padding: 0px; font-size: 16px; line-height: 1.714; font-weight: 400; letter-spacing: -0.005em; color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans", Ubuntu, "Droid Sans", "Helvetica Neue", sans-serif; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: pre-wrap; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgba(255, 255, 255, 0.6); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;'>This Universal Task allows Stonebranch users to perform end-to-end Orchestration and Automation of Jobs &amp; Clusters in Databricks environment either in AWS or Azure. &nbsp;</p>
<p data-renderer-start-pos="724" style='margin: 0.75rem 0px 0px; padding: 0px; font-size: 16px; line-height: 1.714; font-weight: 400; letter-spacing: -0.005em; color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans", Ubuntu, "Droid Sans", "Helvetica Neue", sans-serif; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: pre-wrap; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgba(255, 255, 255, 0.6); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;'><strong data-renderer-mark="true">Key Features:</strong>&nbsp;</p>
<ul class="ak-ul" data-indent-level="1" style='margin: 12px 0px 0px; padding: 0px 0px 0px 24px; box-sizing: border-box; list-style-type: disc; display: flow-root; color: rgb(23, 43, 77); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans", Ubuntu, "Droid Sans", "Helvetica Neue", sans-serif; font-size: 16px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: pre-wrap; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: rgba(255, 255, 255, 0.6); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;'>
    <li>
        <p data-renderer-start-pos="742" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">This task uses python modules <span class="code" data-renderer-mark="true" style='background-color: rgba(9, 30, 66, 0.08); overflow: auto; font-size: 13.712px; font-weight: normal; padding: 2px 0px; -webkit-box-decoration-break: clone; border-radius: 3px; border-style: none; font-family: SFMono-Medium, "SF Mono", "Segoe UI Mono", "Roboto Mono", "Ubuntu Mono", Menlo, Consolas, Courier, monospace; white-space: pre-wrap; margin: 0px 4px; box-shadow: rgba(9, 30, 66, 0.08) -4px 0px 0px 0px, rgba(9, 30, 66, 0.08) 4px 0px 0px 0px;'>requests</span>&nbsp; to make REST-API calls to the databricks environment</p>
    </li>
    <li style="margin-top: 4px;">
        <p data-renderer-start-pos="838" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">This task will use the Databricks URL and the user bearer token to connect with the databricks environment.&nbsp;</p>
    </li>
    <li style="margin-top: 4px;">
        <p data-renderer-start-pos="950" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Users can perform the below databricks with respect to the databricks jobs.</p>
        <ul class="ak-ul" data-indent-level="2" style="margin: 0px; padding: 0px 0px 0px 24px; box-sizing: border-box; list-style-type: circle; display: flow-root;">
            <li>
                <p data-renderer-start-pos="1028" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Create and list jobs</p>
            </li>
            <li style="margin-top: 4px;">
                <p data-renderer-start-pos="1052" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Get job details</p>
            </li>
            <li style="margin-top: 4px;">
                <p data-renderer-start-pos="1071" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Run now jobs</p>
            </li>
            <li style="margin-top: 4px;">
                <p data-renderer-start-pos="1087" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Run submit jobs</p>
            </li>
            <li style="margin-top: 4px;">
                <p data-renderer-start-pos="1106" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Cancel run jobs</p>
            </li>
        </ul>
    </li>
    <li style="margin-top: 4px;">
        <p data-renderer-start-pos="1127" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Also with respect to databricks cluster, this universal task can perform the below operations</p>
        <ul class="ak-ul" data-indent-level="2" style="margin: 0px; padding: 0px 0px 0px 24px; box-sizing: border-box; list-style-type: circle; display: flow-root;">
            <li>
                <p data-renderer-start-pos="1225" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Create, start and restart a cluster</p>
            </li>
            <li style="margin-top: 4px;">
                <p data-renderer-start-pos="1264" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Terminate a cluster</p>
            </li>
            <li style="margin-top: 4px;">
                <p data-renderer-start-pos="1287" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">Get a cluster info</p>
            </li>
            <li style="margin-top: 4px;">
                <p data-renderer-start-pos="1309" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">List clusters</p>
            </li>
        </ul>
    </li>
    <li style="margin-top: 4px;">
        <p data-renderer-start-pos="1328" style="margin: 0px; padding: 0px; font-size: 1em; line-height: 1.714; font-weight: normal; letter-spacing: -0.005em;">With respect to databricks DBFS, this universal task also provides a feature to upload files larger files &nbsp;&nbsp;</p>
    </li>
</ul>

        
<p>&nbsp;</p>
Please visit this link to find key features, prerequisites, installation instructions, configuration instructions, and examples of how to use this integration. 
<a href="https://docs.stonebranch.com/confluence/display/UC69/UAC+-+Databricks">UAC - Databrick</a>.&nbsp;</li>

