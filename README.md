# HOT-OpenStack
Heat Orchestration Templates for Contrail/OpenContrail

# RUN 

### /autoscaling

* **Heat Single Instance Autoscaling**
<br /><br />
[single_autoscale_env.yaml](https://github.com/savithruml/HOT-OpenStack/blob/master/autoscaling/single_autoscale_env.yaml) depends > [single_instance_scale.yaml](https://github.com/savithruml/HOT-OpenStack/blob/master/autoscaling/single_instance_scale.yaml)<br />
`# heat stack-create <stack-name> -f single_autoscale.yaml -e single_autoscale_env.yaml`

* **Contrail SI Scaling**
<br /><br />
[contrail_si_autoscale.yaml](https://github.com/savithruml/HOT-OpenStack/blob/master/autoscaling/contrail_si_autoscale.yaml) depends > [contrail_si_scale.yaml](https://github.com/savithruml/HOT-OpenStack/blob/master/autoscaling/contrail_si_scale.yaml)<br />
`# heat stack-create <stack-name> -f contrail_si_autoscale.yaml -e contrail_si_autoscale.env`





