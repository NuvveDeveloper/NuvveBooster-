# NuvveBooster-
Engagement Stimulator 
                      </div>
                      <div>
                        <p className="font-medium">Video views</p>
                        <p className="text-sm text-muted-foreground">243 views on your latest video</p>
                      </div>
                    </div>
                    <div className="flex items-center">
                      <div className="bg-pink-100 p-2 rounded-full mr-3">
                        <Heart className="h-4 w-4 text-pink-600" />
                      </div>
                      <div>
                        <p className="font-medium">Likes received</p>
                        <p className="text-sm text-muted-foreground">87 likes across your content</p>
                      </div>
                    </div>
                  </>
                ) : (
                  <div className="text-center py-8 text-muted-foreground">
                    Simulation is not currently active
                  </div>
                )}
              </div>
            </CardContent>
          </Card>
          <Card>
            <CardHeader>
              <CardTitle>Engagement Settings</CardTitle>
              <CardDescription>Configure your simulation parameters</CardDescription>
            </CardHeader>
            <CardContent>
              <div className="space-y-4">
                <div>
                  <label className="block text-sm font-medium mb-1">Simulation Speed</label>
                  <select className="w-full p-2 border rounded">
                    <option>Slow (natural growth)</option>
                    <option>Medium (balanced)</option>
                    <option>Fast (noticeable growth)</option>
                  </select>
                </div>
                <div>
                  <label className="block text-sm font-medium mb-1">Target Audience</label>
                  <select className="w-full p-2 border rounded">
                    <option>General audience</option>
                    <option>Specific interests</option>
                    <option>Geographically targeted</option>
                  </select>
                </div>
                <div className="pt-2">
                  <Button variant="outline" className="w-full">
                    Advanced Settings
                  </Button>
                </div>
              </div>
            </CardContent>
          </Card>
        </div>
      </div>
    </div>
  )
}
"
