#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.
@Library('vs-build-tools') _

def lvVersions = ['2018']

//Dependencies related to scan engine. 
//List<String> dependencies = ['niveristand-scan-engine-fxp-libraries', 'niveristand-scan-engine-module-libraries']

ni.vsbuild.PipelineExecutor.execute(this, 'veristand', lvVersions, dependencies)
diffPipeline('2018')