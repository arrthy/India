#!/usr/bin/env groovy

def applicationName=''
def label=""
def mavenParameters= ''
def mavenGoals = ""
def mavenSettingXML = ''
def parentPom = ""



node ('master') {
	stage('SCM') {
	  checkout([$class: 'GitSCM', branches: [[name: '*/integration/2018-JULY']], doGenerateSubmoduleConfigurations: false, extensions: [[$class: 'CleanBeforeCheckout']], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GITHubUser', url: 'https://github.com/keerthiraj86/India.git']]])
	
	}

}
