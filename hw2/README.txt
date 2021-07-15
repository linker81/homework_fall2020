# Without Baseline
python cs285/scripts/run_hw2.py --env_name cartpole-v0 -n 100 -b 5000 -dsa --exp_name q1_lb_no_rtg_dsa

# Visualize a video of the interaction each 10 iterations
python cs285/scripts/run_hw2.py --env_name cartpole-v0 -n 100 -b 5000 -dsa --video_log_freq 10 --exp_name q1_lb_no_rtg_dsa

# With baseline
python cs285/scripts/run_hw2.py --env_name cartpole-v0 -n 100 -b 1000 -dsa --nn_baseline --exp_name q1_lb_no_rtg_dsa



# To visualize plot of the Average of Reward
python read_results.py ../../data/q1_sb_no_rtg_dsa_CartPole-v1_11-07-2021_12-03-24/events.out.tfevents.1625997804.Titan-WS

