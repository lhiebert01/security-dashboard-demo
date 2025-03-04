# Security Dashboard Demo

This repository contains a collection of HTML files that demonstrate various security dashboards and visualizations. These dashboards are created using Python and popular visualization libraries like Plotly and D3.js.

The dashboards cover the following aspects of security monitoring:

  * **Connection Status:**

      * Real-time visualization of connection attempts, including successful connections, denied connections, and ignored connections.
      * Provides insights into the overall health and security of the system.

  * **Connection Timeline:**

      * A timeline view of connection attempts, highlighting anomalies and suspicious patterns.
      * Helps identify potential threats and attacks.

  * **Port Scan Detection:**

      * Visualizes the number of connection attempts to unique destination ports, helping detect port scan activities.
      * Differentiates between various traffic types for deeper analysis.

  * **Unauthorized Sources:**

      * A heatmap displaying the number of connection attempts from unauthorized source IP addresses.
      * Identifies potential attackers and compromised systems.

  * **User Access Patterns:**

      * A heatmap showing user access patterns to different destinations.
      * Highlights unusual access patterns and potential insider threats.

  * **Security Metrics:**

      * Provides key security metrics such as valid token rate, access denied rate, and connection ignore rate.
      * Offers a quick overview of the system's security posture.

## Usage

The dashboards are designed to be deployed as a demo on Render. You can access the live demo here: [https://security-dashboard-demo.onrender.com/](https://www.google.com/search?q=https://security-dashboard-demo.onrender.com/)

The repository also includes a `security_admin_dashboard.html` file that serves as the main dashboard. This dashboard provides an overview of all the security visualizations and metrics.

## Files

  * `security_admin_dashboard.html`: The main dashboard.
  * `connection_status.html`: Real-time connection status visualization.
  * `connection_timeline.html`: Timeline view of connection attempts.
  * `port_scan.html`: Port scan detection visualization.
  * `unauthorized_sources.html`: Heatmap of unauthorized source IP addresses.
  * `user_access.html`: Heatmap of user access patterns.
  * `security_metrics.html`: Key security metrics visualization.

## Contributing

Feel free to submit pull requests or issues if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

  * Plotly: [https://plotly.com/](https://www.google.com/url?sa=E&source=gmail&q=https://plotly.com/)
  * D3.js: [https://d3js.org/](https://www.google.com/url?sa=E&source=gmail&q=https://d3js.org/)