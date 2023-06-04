# Examples of prompt engineering solutions 

<table>
    <thead>
        <tr>
            <td>NAME</td>
            <td>PROMPT</td>
            <td>DESCRIPTION</td>
            <td>EXAMPLE</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>apache</td>
            <td><code>create deploy apache</code></td>
            <td>Deployment based on Apache server Docker image</td>
            <td><a href="/yaml/app.yaml">app.yaml</a></td>
        </tr>
        <tr>
            <td>liveness-probe</td>
            <td><code>create liveness probe every 30 seconds for apache</code></td>
            <td>Liveness probe on Apache every 30 seconds</td>
            <td><a href="/yaml/app-livenessProbe.yaml">app-livenessProbe.yaml</a></td>
        </tr>
        <tr>
            <td>readiness-probe</td>
            <td><code>create readiness probe</code></td>
            <td>Readiness probe every for 10 seconds</td>
            <td><a href="/yaml/app-readinessProbe.yaml">app-readinessProbe.yaml</a></td>
        </tr>
        <tr>
            <td>volume-mounts</td>
            <td><code>create container with mount volume apache</code></td>
            <td>mounting volume in Apache container</td>
            <td><a href="/yaml/app-volumeMounts.yaml">app-volumeMounts.yaml</a></td>
        </tr>
        <tr>
            <td>cronjob-pod</td>
            <td><code>create cronjob running daily at 12 AM restarting httpd</code></td>
            <td>Cronjob runs daily at 12AM to restart apache service</td>
            <td><a href="/yaml/app-cronjob.yaml">app-cronjob.yaml</a></td>
        </tr>
        <tr>
            <td>job-pod</td>
            <td><code>create job syncing html files from google drive to /tmp</code></td>
            <td>Job syncing html files to /tmp dir</td>
            <td><a href="/yaml/app-job.yaml">app-job.yaml</a></td>
        </tr>
        <tr>
            <td>multicontainer-pod</td>
            <td><code>create multicontainer pod Apache with common volume</code></td>
            <td>create multicontainer pod Apache with common volume</td>
            <td><a href="/yaml/app-multicontainer.yaml">app-multicontainer.yaml</a></td>
        </tr>
        <tr>
            <td>resources-pod</td>
            <td><code>create manifest for cpu,memory resources</code></td>
            <td>limitation of CPU,memory</td>
            <td><a href="/yaml/app-resources.yaml">app-resources.yaml</a></td>
        </tr>
        <tr>
            <td>secret-env-pod</td>
            <td><code>"create secret environment for mysql</code></td>
            <td>random credentials for MySQL database</td>
            <td><a href="/yaml/app-secret-env.yaml">app-secret-env.yaml</a></td>
        </tr>
    </tbody>
</table>
