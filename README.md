# Example of adjusting the legend in Plotly
fig.update_layout(
    legend=dict(
        orientation="h",  # Move legend to horizontal (top/bottom)
        yanchor="bottom",
        y=1.02,  # Adjust the position of the legend
        xanchor="right",
        x=1,
        font=dict(size=10)  # Reduce the font size for better fit
    )
)
