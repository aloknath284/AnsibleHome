Role: ZDP_Artifact_Import_Service
Uses: It is used to download ZDP_Artifact from artifactory and import those artifact to higher enviroment.

List of variable role expects:(Required)

bedrockUrl: "<ZDP_INSTANCE_ADRESS>" #e.g: 'http://192.168.1.235:8080'
buildBaseDir:"<IMPORT_BUILD_BASE_DIR>" #e.g: /home/bedrock/Pro_Dev/CI_CD/ansibleBuild/ImportApi/

artifactoryUrl: "<Artifactory_Absolute_URL>" #e.g: 'http://192.168.1.20:8081/artifactory/ext-release-local/'
artifactName: "<ZDP_Artifacts>"  #e.g: 'artifacts-20190204184846481.zip'


List of optional variable:
newRevision: "<TRUE>/<FALSE>"
updateAllConflicts: "<TRUE>/<FALSE>"
timeout: "<TIME_OUT>"
projectName: "<PROJECT_NAME>" #required when artifactName is a tar file
