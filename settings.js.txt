module.exports = {
    uiPort: process.env.PORT || 1880,

    mqttReconnectTime: 15000,

    serialReconnectTime: 15000,

    debugMaxLength: 1000,

    flowFile: 'flows.json',

    credentialSecret: false,

    editorTheme: {
        projects: {
            enabled: false
        }
    }
}
