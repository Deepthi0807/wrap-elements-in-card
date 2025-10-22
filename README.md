import { Card, CardHeader, CardTitle, CardContent, CardFooter } from "@/components/ui/card"
import { Button } from "@/components/ui/button"

export default function ProfileCard() {
  return (
    <Card className="max-w-sm mx-auto">
      <CardHeader>
        <CardTitle>User Profile</CardTitle>
      </CardHeader>
      
      <CardContent className="space-y-3">
        <p><strong>Name:</strong> Deepthi</p>
        <p><strong>Email:</strong> deepthi@example.com</p>
        <p><strong>Role:</strong> Developer</p>
      </CardContent>

      <CardFooter>
        <Button>View Details</Button>
      </CardFooter>
    </Card>
  )
}
